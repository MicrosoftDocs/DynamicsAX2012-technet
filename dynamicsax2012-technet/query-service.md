---
title: Query Service
TOCTitle: Query Service
ms:assetid: e38c417e-475e-4c5f-8c4c-7c73bb80241a
ms:mtpsurl: https://technet.microsoft.com/library/Gg847959(v=AX.60)
ms:contentKeyID: 35253152
author: Khairunj
ms.date: 11/13/2013
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Query Service 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The query service is one of the Microsoft Dynamics AX system services that enables you to issue a query for data without using an Application Integration Framework (AIF) document service or creating a custom service. The query service returns data in a dataset and implements a paging mechanism so that you can manage large amounts of data returned by a query. The query service is:

  - automatically installed

  - by default, hosted by the Application Object Server (AOS)

  - always available

  - a Windows Communication Foundation (WCF) service that adheres to WCF protocols and standards

## How the Query Service Works

The query service runs the query that you specify and returns the data in a dataset. There are three types of queries that you can call with the query web service:

  - Static query – A query that is already defined in the Application Object Tree (AOT) under the **Queries** node. When you call the query service by using a static query, you pass in the query name as a string. For more information, see [Walkthrough: Calling the Query Service with a Static Query](walkthrough-calling-the-query-service-with-a-static-query.md).

  - User-defined query – A query that is defined by using the [QueryMetadata](https://technet.microsoft.com/library/hh151954\(v=ax.60\)) class. For more information about the query metadata classes, see [Metadata Service Class Diagrams](metadata-service-class-diagrams.md).

  - Dynamic query – A query that is defined in an X++ class that extends the [AifQueryBuilder](https://technet.microsoft.com/library/gg769877\(v=ax.60\)) class. All query logic is contained in the query builder class. Use a dynamic query when:
    
      - You want to use the query service to call a complex query that cannot be created using a static query or a user-defined query.
    
      - You want full control over the query behavior and results.
    
    When you use the query service to call a static or user-defined query, the query service handles the details of how the query is run, for example, the dataset name is defaulted to the name of the query. If you use the [AifQueryBuilder](https://technet.microsoft.com/library/gg769877\(v=ax.60\)) class, you can specify the dataset name in the getDataSetName method.

## Static Query

To use the query service to call a static query, you call the QueryServiceClient.ExecuteStaticQuery method and pass in the name of the query in the AOT. The signature of the ExecuteStaticQuery method is:

DataSet QueryServiceClient.ExecuteStaticQuery(string queryName, ref Paging paging)

The following code example shows the code to call the ExecuteStaticQuery method:

``` csharp
    DataSet dataSet;
    Paging paging = null;

    dataSet = client.ExecuteStaticQuery("CustTable", ref paging);
```

The results of the query are returned in a dataset object. The DataSet.DataSetName property defaults to the name of the query. For example, in the previous code example, the dataSet.DataSetName property returns CustTable. The returned dataset contains a data table for each data source in the query. The dataset also contains a data relation for each relation defined in the query. For more information, see the Query Results Dataset section. For more information about static queries, see [Walkthrough: Calling the Query Service with a Static Query](walkthrough-calling-the-query-service-with-a-static-query.md).

## User-Defined Query

To use the query service to call a user-defined query, you first create a query using the [QueryMetadata](https://technet.microsoft.com/library/hh151954\(v=ax.60\)) class and other metadata classes such as the [QueryDataSourceMetadata](https://technet.microsoft.com/library/hh130664\(v=ax.60\)) class, the [QueryRelationMetadata](https://technet.microsoft.com/library/hh130249\(v=ax.60\)) class, and the [QueryFieldMetadata](https://technet.microsoft.com/library/hh188130\(v=ax.60\)) class. Then you call the QueryServiceClient.ExecuteQuery method and pass in the query object. The signature of the ExecuteQuery method is:

DataSet QueryServiceClient.ExecuteQuery(QueryMetadata queryMetadata, ref Paging paging)

Creating a query to pass into the query service is a similar process to creating a query in the AOT. For more information, see [How to: Create Queries by using the AOT](https://technet.microsoft.com/library/bb314753\(v=ax.60\)). For each query, you specify the query name and type. Then you define the query data sources and any relations between the data sources.

The following code example shows the code to call the ExecuteQuery method:

``` csharp
    QueryServiceClient client = new QueryServiceClient();

    DataSet dataSet;
    Paging paging = null;

    QueryMetadata query;
    QueryDataSourceMetadata customerDataSource;

    query = new QueryMetadata();

    // Set the properties of the query.
    query.QueryType = QueryType.Join;
    query.AllowCrossCompany = true;
    query.DataSources = new QueryDataSourceMetadata[1];

    // Set the properties of the Customers data source.
    customerDataSource = new QueryDataSourceMetadata();
    customerDataSource.Name = "Customers";
    customerDataSource.Enabled = true;
    customerDataSource.FetchMode = FetchMode.OneToOne;
    customerDataSource.Table = "CustTable";
    // Setting DynamicFieldList property to true returns all fields.
    customerDataSource.DynamicFieldList = true;
    //Add the data source to the query.
    query.DataSources[0] = customerDataSource;

    // Execute the query you just created.
    dataSet = client.ExecuteQuery(query, ref paging);
```

The query results are returned in a System.DataSet object. For more information, see the Query Results Dataset section.

## Dynamic Query

To use the query service to call a dynamic query, you first create a query in X++ by creating a class that extends the [AifQueryBuilder](https://technet.microsoft.com/library/gg769877\(v=ax.60\)) class. Then you call the QueryServiceClient.ExecuteDynamicQuery method and pass in the name of the X++ query class and any query arguments. Query arguments are passed to the query builder class using a class that extends the [AifQueryBuilderArgs](https://technet.microsoft.com/library/gg769894\(v=ax.60\)) class. The signature of the ExecuteDynamicQuery method is:

DataSet QueryServiceClient.ExecuteDyanmicQuery(string queryBuilderName, QueryBuilderArgs queryBuilderArgs, ref Paging paging)

The following code example shows the code to call the ExecuteDynamicQuery:

``` csharp
    QueryServiceClient client = new QueryServiceClient();

    DataSet dataSet;
    Paging paging = null;

    CustTransQueryBuilderArgs args = new CustTransQueryBuilderArgs() { parmCustAccount = "4008" };
    dataSet = client.ExecuteDynamicQuery("CustTransQueryBuilder", args, ref paging);
```

## Query Results Dataset

Regardless of how you call the query service, the query results are returned in a System.DataSet object. Characteristics of the dataset include the following.

  - The DataSet.DataSetName property defaults to the name of the query or the name of the query builder class, if you are calling a dynamic query.

  - The dataset contains a data table for each query data source. Each data table contains a column that corresponds to a query data source field returned by the query. The data table column name and data type correspond to the name and data type of the query data source field.

  - All relations between the same query data sources become a single, multi-column, unconstrained relation between corresponding tables. The data source on which the relation is defined becomes the child table and the related data source is the parent table. The naming convention for each relation is \<Relation JoinDataSource\>\_\<Relation CurrentDataSource\> as defined in the relation properties JoinDataSource and CurrentDataSource in the AOT. Therefore, a relation between the CustTable data source and the CustTrans data source becomes a table relation in the dataset named CustTable\_CustTrans.

  - If the query returns no records then the dataset data tables will be empty.

## Query Service Security

There are two types of security to consider when you are working with the query service:

1.  Access security– who can access the query service

2.  Data security – what data can a user access by using the query service

Only authenticated Microsoft Dynamics AX users can access the query service. In order to retrieve data by using the query service, you must have a valid username in Microsoft Dynamics AX. The query service uses Windows integrated security. Therefore, when a caller invokes the query service, the system verifies the credentials under which the calling client is running and verifies that the username is a valid Microsoft Dynamics AX user.

The data that a caller can access by using the query service depends on what roles the user is a member of. The query service respects any security that is implemented for the calling user. For more information, see Query Service Security.

## Query Service Architecture

The query service is a WCF service that is contained in the Microsoft.Dynamics.AX.Services.QueryService.dll assembly. This assembly is located in the server Bin directory. Depending on your configuration, the assembly is located in a directory such as C:\\Program Files\\Microsoft Dynamics AX\\\<version\>\\Server\\MicrosoftDynamicsAX\\Bin.

The query service has the following configuration default values:

  - It is hosted by the AOS on port 8201 and the URL is net.tcp//\<servername\>:8201/DynamicsAx/Services/QueryService.

  - The service WSDL URL is http://\<servername\>:8101/DynamicsAx/Services/QueryService

  - It uses the netTcpBinding binding.

These settings will vary depending on what port number the service port and the WSDL port have been configured to use. The configuration settings for the query service are found in the Ax32Serv.config file which is also located in the server Bin directory.

## Handling Large Datasets

There are two ways you can handle query service calls that return large amounts of data:

1.  Paging – lets you retrieve the data one page at a time using the paging object. You have two options when you implement paging: position-based paging and value-based paging. For more information, see [Paging and Query Service Results](paging-and-query-service-results.md).

2.  Streaming – lets you retrieve all the data in a single stream. For more information, see [Streaming and Query Service Results](streaming-and-query-service-results.md).

For more information see, [Handling Large Datasets Returned by the Query Service](handling-large-datasets-returned-by-the-query-service.md).

## See also

[Walkthrough: Calling the Query Service with a Static Query](walkthrough-calling-the-query-service-with-a-static-query.md)

[Query Service Security](query-service-security.md)

[Handling Large Datasets Returned by the Query Service](handling-large-datasets-returned-by-the-query-service.md)

