---
title: AIF Class Naming Conventions
TOCTitle: AIF Class Naming Conventions
ms:assetid: 16011911-1345-41d8-9c7d-5f9a21048942
ms:mtpsurl: https://technet.microsoft.com/library/Cc583680(v=AX.60)
ms:contentKeyID: 35240633
author: Khairunj
ms.author: daxcpft
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# AIF Class Naming Conventions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following table lists the naming conventions for the Application Integration Framework (AIF) classes. If you are creating your own services, it is a best practice to follow these naming conventions.


> [!NOTE]
> <P>The document class artifact is the top-level data object. It is referred to as the document class, but is also a data object.</P>



<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Artifact type</p></th>
<th><p>Name description</p></th>
<th><p>Name generation rules</p></th>
<th><p>Example</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Document name</p></td>
<td><p>Name of the document</p></td>
<td><p>User-defined name describing the document</p></td>
<td><p>SalesOrder</p></td>
</tr>
<tr class="even">
<td><p>Service class</p></td>
<td><p>Name of the AIF service class</p></td>
<td><p>&lt;Prefix&gt; + &lt;Document Name&gt; + &quot;Service&quot;</p></td>
<td><p>SalesSalesOrderService</p></td>
</tr>
<tr class="odd">
<td><p>Document class</p></td>
<td><p>Name of the X++ class for the root data object</p></td>
<td><p>&lt;Prefix&gt; + &lt;Document Name&gt;</p></td>
<td><p>SalesSalesOrder</p></td>
</tr>
<tr class="even">
<td><p>Data objects</p></td>
<td><p>Name of the X++ class for the child data objects of the document class</p></td>
<td><p>&lt;Root data object name&gt; + &quot;_&quot; + &lt;Query data source Name&gt;</p></td>
<td><p>SalesSalesOrder_SalesTable, SalesSalesOrder_DocuRefHeader, SalesSalesOrder_DocuRefLine, SalesSalesOrder_InventDim, SalesSalesOrder_MarkupTransHeader, SalesSalesOrder_MarkupTransLine, SalesSalesOrder_SalesLine</p></td>
</tr>
<tr class="odd">
<td><p>AOT service node</p></td>
<td><p>Name of the AOT node for the service</p></td>
<td><p>&lt;Prefix&gt; + &lt;Document Name&gt; + &quot;Service&quot;</p></td>
<td><p>SalesSalesOrderService</p></td>
</tr>
<tr class="even">
<td><p>Service external name</p></td>
<td><p>Name of the service published to Windows Communication Foundation (WCF)</p></td>
<td><p>&lt;Document Name&gt; + &quot;Service&quot;</p></td>
<td><p>SalesOrderService</p></td>
</tr>
<tr class="odd">
<td><p>Table class names</p></td>
<td><p>Name of the Ax &lt;Table&gt; classes</p></td>
<td><p>&quot;Ax&quot; + query data source table name</p></td>
<td><p>AxSalesTable, AxInventDim, AxDocuRef, AxMarkupTrans, AxSalesLine</p></td>
</tr>
<tr class="even">
<td><p>Query</p></td>
<td><p>Name of the query</p></td>
<td><p>&quot;Axd&quot; + user-defined document name</p></td>
<td><p>AxdSalesOrder</p></td>
</tr>
<tr class="odd">
<td><p>Document class name</p></td>
<td><p>Name of the Axd &lt;Document&gt; class</p></td>
<td><p>Same name as the query</p></td>
<td><p>AxdSalesOrder</p></td>
</tr>
</tbody>
</table>


## See also

[Document Services Classes](document-services-classes.md)

[About Document Service Classes](about-document-service-classes.md)

[About Axd\<Document\> Classes](about-axd-document-classes.md)

[About Ax\<Table\> Classes](about-ax-table-classes.md)

