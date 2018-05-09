---
title: Handling Large Datasets Returned by the Query Service
TOCTitle: Handling Large Datasets Returned by the Query Service
ms:assetid: 6ad0a766-bf37-43e0-a093-0a781c9b8012
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg840967(v=AX.60)
ms:contentKeyID: 35244792
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Handling Large Datasets Returned by the Query Service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Dynamics AX query service provides two ways for handling the return of large datasets:

  - Paging – The client application uses a paging object to return all query result records up to the maximum record limit. You can use paging when you call a static, a user-defined, or a dynamic query.

  - Streaming – The client application reads all the query result records until the end of file (EOF) is reached. You can use streaming only when you call a user–defined or a dynamic query.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Query type</p></td>
<td><p>Supports paging</p></td>
<td><p>Query service method</p></td>
<td><p>Supports streaming</p></td>
<td><p>Query service method</p></td>
</tr>
<tr class="even">
<td><p>Static</p></td>
<td><p>Yes</p></td>
<td><p>ExecuteStaticQuery</p></td>
<td><p>No</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>User-defined</p></td>
<td><p>Yes</p></td>
<td><p>ExecuteQuery</p></td>
<td><p>Yes</p></td>
<td><p>ExecuteStreamedQuery</p></td>
</tr>
<tr class="even">
<td><p>Dynamic</p></td>
<td><p>Yes</p></td>
<td><p>ExecuteDynamicQuery</p></td>
<td><p>Yes</p></td>
<td><p>ExecuteStreamedDynamicQuery</p></td>
</tr>
</tbody>
</table>


## Paging

In order to implement paging, you must pass a paging object parameter together with the query specification. The paging object enables you to write code to handle a query that returns large amounts of data. The query service paging functionality includes two types of paging:

  - Position-based paging – You supply a start position and the record limit for each query data source. The start position is a numeric value that specifies the record position (in the results) from which you want to start paging.

  - Value-based paging – You provide a bookmark and the record limit for each query data source. The bookmark is an identifier that is derived from the value of the record that specifies the record position (in the results) from which you want to start paging.

If you pass a NULL paging object to the query service, it will not use any paging and will return all records for the specified query up to the maximum record limit. For more information about paging and the query service, see [Paging and Query Service Results](paging-and-query-service-results.md).

Paging is useful when you may or may not want to read all of the data returned by a query. For example, you may want to use paging with an interactive user interface where user action determines whether more data is displayed.

## Streaming

When you call a query that returns a large amount of data, you can use streaming to read all of the data that is returned. If you want to use streaming, you must use one of the following query service methods:

  - ExecuteStreamedQuery – Call this method when you are using the query service with a user-defined query.

  - ExecuteStreamedDynamicQuery – Call this method when you are using the query service with a dynamic query.


> [!NOTE]
> <P>You cannot use streaming when you call the query service and use a static query.</P>



For more information about how to implement streaming, see [Streaming and Query Service Results](streaming-and-query-service-results.md).

Streaming is useful for any scenario in which you want to read all of the data returned by a query, for example, when you are retrieving data for a report.

## Upper Record Limit

From a single call to the query service, the default maximum number of rows that can be returned from a query data source is 25,000. This means that each data table in the dataset returned by the query service can have up to 25,000 records if you do not specify a record limit.

## See also

[Paging and Query Service Results](paging-and-query-service-results.md)

[Streaming and Query Service Results](streaming-and-query-service-results.md)

