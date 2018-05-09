---
title: Paging and Query Service Results
TOCTitle: Paging and Query Service Results
ms:assetid: 03ac49bb-14ef-4210-93b6-a51263a9cb9c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg843447(v=AX.60)
ms:contentKeyID: 35240242
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Paging and Query Service Results 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Dynamics AX query service supports paging so that you can manage the amount of data returned by a query. Paging provides a mechanism to stop the query in order to limit the amount of data per request. This paging mechanism also allows for the query to restart from the position where it was stopped.

This topic describes the different types of paging that are available and shows you how to implement them when you call the query service. The two types of paging are as follows:

  - Position-based paging – You supply a start position and the record limit for each query data source. The start position is a numeric value that specifies the record position (in the results) from which you want to start paging.

  - Value-based paging – You provide a bookmark and the record limit for each query data source. The bookmark is an identifier that is derived from the value of the record.


> [!TIP]
> <P>The following examples use the CustTable query and the query service will return data for the default company of the calling user. Therefore, you should ensure that you have data for that company in the CustTable table.</P>



When you call the query service, you pass the paging parameters to the service by using one of the paging classes exposed by the query service.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Managed Paging Class</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh186334(v=ax.60)">Microsoft.Dynamics.AX.Framework.Services.QueryService.Paging</a></p></td>
<td><p>Abstract class that all the other paging classes extend.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh153285(v=ax.60)">Microsoft.Dynamics.AX.Framework.Services.QueryService.PositionBasedPaging</a></p></td>
<td><p>Class used for position-based paging.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh131386(v=ax.60)">Microsoft.Dynamics.AX.Framework.Services.QueryService.TopLevelValueBasedPaging</a></p></td>
<td><p>Class used for top-level value-based paging.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh187684(v=ax.60)">Microsoft.Dynamics.AX.Framework.Services.QueryService.ValueBasedPaging</a></p></td>
<td><p>Class used for value-based paging. Extends the <a href="https://technet.microsoft.com/en-us/library/gg769928(v=ax.60)">AifQueryPaging</a> class.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh187248(v=ax.60)">Microsoft.Dynamics.AX.Framework.Services.QueryService.ValueBasedPagingBase</a></p>
<p></p></td>
<td><p>Abstract class that extends the <a href="https://technet.microsoft.com/en-us/library/gg769928(v=ax.60)">AifQueryPaging</a> class.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://technet.microsoft.com/en-us/library/hh153260(v=ax.60)">Microsoft.Dynamics.AX.Framework.Services.QueryService.AdvancedValueBasedPaging</a></p></td>
<td><p>Class used for advanced value-based paging. Extends the <a href="https://technet.microsoft.com/en-us/library/gg759741(v=ax.60)">AifValueBasedQueryPagingBase</a> class.</p></td>
</tr>
</tbody>
</table>


## Position-Based Paging

Position-based paging is the simplest form of paging in which you specify a starting position and a record limit. In the dataset returned from the query service, there is a table for each data source in the query. By using position-based paging, no table returned from a query request will contain more than the number of records specified in the record limit.

The following code shows you how to use position-based paging when you call the query service by using the CustTable static query. The Paging object is passed by reference so, after you make the first call to the ExecuteStaticQuery method, the starting position value is returned to the client. The starting position value will be the position of the last record returned plus one.

In this example, each table in the dataset can have no more than 10 records. In order to get all of the records, the code must call the query service to get the next page of data until the top-level dataset table no longer contains any rows.

``` csharp
static void Main(string[] args)
        {

            QueryServiceClient client = new QueryServiceClient();

            int i = 0;
            DataSet dataSet;
            Paging paging = new PositionBasedPaging() { StartingPosition = 1, NumberOfRecordsToFetch = 10 };

            do
            {
                // Call the CustTable query using the query service.
                dataSet = client.ExecuteStaticQuery("CustTable", ref paging);

                // Code to perform operations on the data returned.
                Console.WriteLine("Query service call: " + i.ToString());
                Console.WriteLine("Number of Records in CustTable: " + dataSet.Tables[0].Rows.Count.ToString());
                Console.WriteLine("Number of Records in CustTrans: " + dataSet.Tables[1].Rows.Count.ToString());
                Console.WriteLine("Number of Records in CustTransOpen: " + dataSet.Tables[2].Rows.Count.ToString());
                i++;
            }
            // Check if the last call returned any data. If so, then this is the next page of data.
            while (dataSet.Tables[0].Rows.Count > 0);

            Console.ReadLine();
        }
```


> [!IMPORTANT]
> <P>When you use position-based paging, you must explicitly set the sort order in your query so that the data is grouped correctly when it is returned to the client.</P>



## Value-Based Paging

When you use value-based paging, you specify a bookmark that defines where the data page starts and you specify a record limit.

There are three different methods for using value-based paging:

  - Standard value-based paging – You specify a bookmark and a record limit.

  - Top-level value-based paging – You specify a bookmark and a record limit that is applied only to the top-level data source in the query.

  - Advanced value-based paging – You specify a bookmark and a record limit for each query data source

### Standard Value-Based Paging

When you use value-based paging, you must specify a bookmark and a record limit. If you pass no bookmark, the paging will start at the beginning of the result set. In the dataset returned from the query service, there is a table for each query data source. By using standard value-based paging, no table returned from a query request will contain more than the number of records specified in the record limit.

The following code shows you how to use standard value-based paging when you call the query service by using a static query. In value-based paging, you use the bookmark to check if there is any more data returned from the query. For the first call to the ExecuteStaticQuery method, you set no bookmark value. The Paging object is passed by reference so after you make the first call to the ExecuteStaticQuery method, the Paging object contains the bookmark of the first record in the next page of data. If there are more records to be returned, the bookmark returned to the client is not NULL. If there are no more records to be returned, the bookmark is NULL.

``` csharp
static void Main(string[] args)
        {

            QueryServiceClient client = new QueryServiceClient();

            int i = 0;
            DataSet dataSet;
            Paging paging = new ValueBasedPaging() { RecordLimit = 10 };

            do
            {
                // Call the CustTable query using the query service.
                dataSet = client.ExecuteStaticQuery("CustTable", ref paging);

                // Code to perform operations on the data returned.
                Console.WriteLine("Query service call: " + i.ToString());
                Console.WriteLine("Number of Records in CustTable: " + dataSet.Tables[0].Rows.Count.ToString());
                Console.WriteLine("Number of Records in CustTrans: " + dataSet.Tables[1].Rows.Count.ToString());
                Console.WriteLine("Number of Records in CustTransOpen: " + dataSet.Tables[2].Rows.Count.ToString());
                i++;
            }
            // Check if the returned bookmark is NULL. If so, there is no more data to be returned.
            while (((ValueBasedPaging)paging).Bookmark != null);

            Console.ReadLine();

        }
```

By default, if you pass a NULL Paging object to the query service, it will use standard value-based paging. After you call the query, if there is more data to be returned, the query service will return a Paging object to you with a bookmark so that you can retrieve the next page of data.

### Top-Level Value-Based Paging

When you use top-level value-based paging, you must specify a bookmark, a record limit, and a Boolean value for the LimitTopLevelDataSourcesOnly parameter. If you pass no bookmark, the paging will start at the beginning of the result set.

In the dataset returned from the query service, there is a table for each query data source. In top-level value-based paging, the record limit applies only to the parent data source in the query. So the parent table in the dataset will contain no more than the number of records specified in the record limit. The maximum record limit is applied to the child data sources in the query. Therefore, if you call the CustTable query and pass in a record limit of 10, the dataset returned will contain a CustTable table that contains no more than 10 records, but the CustTrans and CustTransOpen tables will contain all the records that are returned for those data sources by the query up to the maximum record limit of 25,000.

The following code shows you how to use top-level value-based paging when you call the query service by using a static query. In top-level value-based paging, you use the bookmark to check if there is any more data returned from the query. For the first call to the ExecuteStaticQuery method, you set no bookmark value. The Paging object is passed by reference so after you make the first call to the ExecuteStaticQuery method, the Paging object contains the bookmark of the first record in the next page of data. If there are more records to be returned, the bookmark returned to the client is not NULL. If there are no more records to be returned, the bookmark is NULL.

``` csharp
static void Main(string[] args)
        {
            QueryServiceClient client = new QueryServiceClient();

            int i = 0;
            DataSet dataSet;
            Paging paging = new TopLevelValueBasedPaging() { RecordLimit = 25, LimitTopLevelDataSourcesOnly = true };

            do
            {
                // Call the CustTable query using the query service.
                dataSet = client.ExecuteStaticQuery("CustTable", ref paging);

                // Code to perform operations on the data returned.
                Console.WriteLine("Query service call: " + i.ToString());
                Console.WriteLine("Number of Records in CustTable: " + dataSet.Tables[0].Rows.Count.ToString());
                Console.WriteLine("Number of Records in CustTrans: " + dataSet.Tables[1].Rows.Count.ToString());
                Console.WriteLine("Number of Records in CustTransOpen: " + dataSet.Tables[2].Rows.Count.ToString());
                i++;
            }
            // Check if the last call returned any data. If so, then this is the next page of data.
            while (((ValueBasedPaging)paging).Bookmark != null);

            Console.ReadLine();
        }
```

### Advanced Value-Based Paging

Advanced value-based paging enables you to control the record limit for each data source in a query. When you use advanced value-based paging, you can specify a bookmark and a record limit for each query data source. Any data source for which a record limit is not specified will return up to the maximum record limit of 25,000.

In the dataset returned from the query service, there is a table for each query data source. In advanced value-based paging, the record limits are applied for each data source in the query. If you do not provide a record limit for query data source, the maximum record limit is applied. If you run the following code, the query service returns a dataset that contains a CustTable table that contains up to 2 records, a CustTrans table that contains up to 10 records, and a CustTransOpen table that contains up to 10 records.

The following code shows you how to use advanced value-based paging when you call the query service by using a static query. In advanced value-based paging, you use the bookmark to check if there is any more data returned from the query. For the first call to the ExecuteStaticQuery method, you set no bookmark value. The Paging object is passed by reference so after you make the first call to the ExecuteStaticQuery method, the Paging object contains the bookmark of the first record in the next page of data. If there are more records to be returned, the bookmark returned to the client is not NULL. If there are no more records to be returned, the bookmark is NULL.

``` csharp
static void Main(string[] args)
        {
            QueryServiceClient client = new QueryServiceClient();

            int i = 0;
            DataSet dataSet;
            AdvancedValueBasedPaging advPaging = new AdvancedValueBasedPaging();
            Paging paging = advPaging;

            advPaging.RecordLimits = new DataSourceRecordLimit[] {
                new DataSourceRecordLimit() { DataSourceName = "CustTable", RecordLimit = 2 },
                new DataSourceRecordLimit() { DataSourceName = "CustTrans", RecordLimit = 10 },
                new DataSourceRecordLimit() { DataSourceName = "CustTransOpen", RecordLimit = 10 }};

            do
            {
                // Call the CustTable query using the query service.
                dataSet = client.ExecuteStaticQuery("CustTable", ref paging);

                // Code to perform operations on the data returned.
                Console.WriteLine("Query service call: " + i.ToString());
                Console.WriteLine("Number of Records in CustTable: " + dataSet.Tables[0].Rows.Count.ToString());
                Console.WriteLine("Number of Records in CustTrans: " + dataSet.Tables[1].Rows.Count.ToString());
                Console.WriteLine("Number of Records in CustTransOpen: " + dataSet.Tables[2].Rows.Count.ToString());
                i++;
            }
            // Check if the last call returned any data. If so, then this is the next page of data.
            while (((AdvancedValueBasedPaging)paging).Bookmark != null);

            Console.ReadLine();
        }
```

It is not required to set a record limit for each query data source. However, the query will stop processing as soon as a record limit on any data source is reached.

## See also

[Handling Large Datasets Returned by the Query Service](handling-large-datasets-returned-by-the-query-service.md)

[Streaming and Query Service Results](streaming-and-query-service-results.md)

[Walkthrough: Calling the Query Service with a Static Query](walkthrough-calling-the-query-service-with-a-static-query.md)

