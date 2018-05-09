---
title: Set up financial dimensions for integrating applications (Excel and Management Reporter)
TOCTitle: Set up financial dimensions for integrating applications (Excel and Management Reporter)
ms:assetid: aeb68efa-fdaa-47d3-8119-3139eab8d29d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507086(v=AX.60)
ms:contentKeyID: 59623137
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.DimensionIntegrationConfiguration
- MsDynAx060.Forms.DimensionIntegrationConfiguration
---

# Set up financial dimensions for integrating applications (Excel and Management Reporter) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to specify the financial dimensions that are available in lookups in Microsoft Excel when you use Office Add-ins for Microsoft Dynamics AX, and the order in which financial dimensions are displayed in Management Reporter for Microsoft Dynamics ERP. You might use this functionality to bring financial dimensions into a budget planning worksheet in Excel, or to develop financial statements in Management Reporter.

This procedure describes functionality that is available in Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Setup</p></td>
<td><p>Set up financial dimensions and financial dimension values. For more information, see the following topics:</p>
<ul>
<li><p><a href="create-a-financial-dimension.md">Create a financial dimension</a></p></li>
<li><p><a href="https://technet.microsoft.com/en-us/library/hh242667(v=ax.60)">Financial dimension values (form)</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up financial dimension attributes for Office Add-ins

Use this procedure to specify the financial dimensions that are available in lookups in Office Add-ins for Microsoft Dynamics AX. For more information, see [Using the Microsoft Dynamics AX Add-in for Excel](using-the-microsoft-dynamics-ax-add-in-for-excel.md).

To set up financial dimension attributes for Office Add-ins, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Financial dimensions** \> **Financial dimension configuration for integrating applications**.

2.  In the **Office Add-ins** area, select the financial dimensions that can be used as document data sources in applications such as Microsoft Excel.
    
    The dimensions that you select will be available in lookups in Excel, as long as the financial dimensions are active. A financial dimension is active if the Microsoft Dynamics AX system date is in the range that is indicated by the **Active from** and **Active to** fields in the **Financial dimension values** form. If the financial dimension is inactive, it is not displayed in lookups in Excel.

3.  Click **Close**. A custom query is created, and a custom document data source is created and activated, for each financial dimension that you selected. If a query that has the default query name already exists for a financial dimension, a message is displayed, and you can enter a unique name for the query.

4.  Optional: Verify that the document data sources were created. Click **Organization administration** \> **Setup** \> **Document management** \> **Document data sources**.

## 2\. Set up financial dimension attributes for Management Reporter

Use this procedure to specify the order in which financial dimensions are displayed in Management Reporter. For more information about Management Reporter, see [Management Reporter for Microsoft Dynamics ERP](http://go.microsoft.com/fwlink/?linkid=324762).

To set up financial dimension attributes for Management Reporter, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Financial dimensions** \> **Financial dimension configuration for integrating applications**.

2.  In the **Management Reporter** area, arrange the dimension attributes in the order they should be displayed in Management Reporter.
    
    If new financial dimensions are added after you specify the order in this form, the dimensions are added to the end of the list by default. If dimensions are removed from Microsoft Dynamics AX, they are removed from the list in Management Reporter.

## Related tasks

[Create a financial dimension](create-a-financial-dimension.md)

[Setting up the chart of accounts](setting-up-the-chart-of-accounts.md)

[Setting up traditional financial statements](setting-up-traditional-financial-statements.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up financial dimensions for integrating applications, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>Maintain document handling</strong> (DocumentHandlingMaintain)</p></li>
<li><p><strong>View financial dimensions</strong> (DimensionDetailsView</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Financial dimensions (form)](https://technet.microsoft.com/en-us/library/hh209534\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

