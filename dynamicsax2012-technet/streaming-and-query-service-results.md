---
title: Streaming and Query Service Results
TOCTitle: Streaming and Query Service Results
ms:assetid: d05f2ad0-41c2-447e-a5b9-865771e4e2b1
ms:mtpsurl: https://technet.microsoft.com/library/Gg881176(v=AX.60)
ms:contentKeyID: 35251817
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Streaming and Query Service Results 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you use the Microsoft Dynamics AX query service to call a query that returns a large amount of data, you can use streaming to read all of the data that is returned.

## How Streaming Works

If you want to use streaming, you must call one of the following methods.

  - ExecuteStreamedQuery – call this method when using the query service with a user-defined query.

  - ExecuteStreamedDynamicQuery – call this method when using the query service with a dynamic query.

When you call one of the query service methods that returns data in a stream, you must pass in an int value for the pageSize parameter. The pageSize parameter specifies the maximum number of records per page in the stream. The default maximum record limit is 25,000. If you attempt to set the pageSize parameter to a value larger than the record limit, you will receive an error.

Even though all the data is returned to the client in a stream, the stream is actually a structure of pages. Each page in the stream begins with an int64 value that specifies the number of bytes in the page. You can then use this value to read the page and then move on to the next page in the stream.

## See also

[Handling Large Datasets Returned by the Query Service](handling-large-datasets-returned-by-the-query-service.md)

[Paging and Query Service Results](paging-and-query-service-results.md)

