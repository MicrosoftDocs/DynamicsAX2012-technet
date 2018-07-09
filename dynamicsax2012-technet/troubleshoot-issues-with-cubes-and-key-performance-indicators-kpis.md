---
title: Troubleshoot issues with cubes and key performance indicators (KPIs)
TOCTitle: Troubleshoot issues with cubes and key performance indicators (KPIs)
ms:assetid: aaadaba3-f3c5-4ebd-b867-95f146347d51
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677280(v=AX.60)
ms:contentKeyID: 49384051
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Troubleshoot issues with cubes and key performance indicators (KPIs) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information that can help you troubleshoot issues that you may encounter when you work with cubes and key performance indicators (KPIs) included with Microsoft Dynamics AX.

## When deploying cubes, you receive an error that says you can’t connect to the OLAP server

During cube deployment, the **Infolog** form appears and displays the following error:

*Unable to connect to the OLAP server name currently set as the default: \[SSASServerName\]. Please ensure that it is a valid OLAP server instance and that it is running. The value can be changed in the Analysis Servers form.*

To resolve this issue, complete the following tasks:

  - Verify that a [supported version](http://www.microsoft.com/en-us/download/details.aspx?id=11094) of Microsoft SQL Server Analysis Services is installed and running.

  - If you use Windows Firewall to help protect your computers, verify that the firewall is configured to allow access to Analysis Services. By default, Analysis Services uses port 2383, so you may need to exclude that port. For more information, see [Configure the Windows Firewall to Allow Analysis Services Access](http://msdn.microsoft.com/en-us/library/ms174937.aspx).

## Users cannot add or modify KPIs

Users may receive the following message when they try to add or modify KPIs in Enterprise Portal for Microsoft Dynamics AX:

*An unexpected error occurred while processing the Business overview Web part. Contact your system administrator.*

This situation occurs under the following conditions:

  - Users access Enterprise Portal on a computer that is not the SharePoint server.

  - Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack is installed.

To resolve this issue, follow these steps.

1.  Install the [Knowledgebase 2744197](https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2744197) hotfix.

2.  Assign the proxy account for the Business Connector to the server administrator role in Analysis Services. Follow these steps:
    
    1.  Open SQL Server Management Studio and connect to your instance of Analysis Services.
    
    2.  In the tree view, right-click the Analysis Services instance, and then click **Properties**. The **Analysis Services Properties** window is displayed.
    
    3.  In the **Select a page** area, click **Security**.
    
    4.  Click **Add**. The **Select Users or Groups** form is displayed.
    
    5.  Enter the Business Connector proxy account in the following format: \[DomainName\]\\\[UserName\]. Click **OK**.

## You cannot process cubes because the provider is not registered

You may receive the following error when processing an Analysis Services project using the Analysis Services Project Wizard:

*The provider 'SQLNCLI11.1' is not registered.*

To resolve this issue, verify that the Analysis Services data source has the correct provider by completing the following steps.

1.  In SQL Server Management Studio, connect to your Analysis Services instance.

2.  In the tree view, expand the **Databases** \> **\[Database Name\]** \> **Data Sources** node.

3.  Right-click the **Dynamics Database** data source and choose **Properties**.

4.  In the **Connection String** row, verify that the provider is correct.
    
      - If you are using Analysis Services 2008, the provider should be **SQLNCLI10.1**.
    
      - If you are using Analysis Services 2008 R2, the provider should be **SQLNCLI10.1**.
    
      - If you are using Analysis Services 2012, the provider should be **SQLNCLI11.1**.

5.  Click **OK** to save your changes.

## When processing a cube, you see errors related to an attribute key

When processing a cube, you may see errors that indicate that an attribute key was converted to an unknown member. These errors are similar to the following:

  - Errors in the OLAP storage engine: The attribute key cannot be found when processing: Table: 'CUSTINVOICETRANSEXPANDED', Column: 'INVENTSTYLEID', Value: ''. The attribute is 'Styles'.

  - Errors in the OLAP storage engine: The attribute key was converted to an unknown member because the attribute key was not found. Attribute Styles of Dimension: Styles from Database: Dynamics AX initial, Cube: Sales cube, Measure Group: Customer invoice lines, Partition: Customer invoice lines, Record: 1.

These messages indicate that there is not a valid join between a measure and a dimension for that record. When creating a join, if a record is not in both tables, the join will not be as expected. In this case, the record gets placed in an unknown or N/A bucket when you view the cube data.

Consider the following examples:

  - An invoice line has an item associated with it. In case of free text invoices, there may not be an item associated with an invoice line. For free text invoices, the item field is empty by design.

  - Employees that are active do not have a “retired date”. In the employee fact table, the Retired date field contains the NULL date value, 1/1/1900, by design.

  - If the zip code field has no validation in Microsoft Dynamics AX and a customer record has an invalid zip code, 99999, it would be an outlier. Possibly the customer did not provide one.

You can handle these errors in the following ways:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Action</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Take no action.</p></td>
<td><p>Understand that when viewing reports and cube data, the unknown or N/A bucket represents the values that do not line up with the joins that are in the dimension usage.</p></td>
</tr>
<tr class="even">
<td><p>Change the dimension data source view (DSV) to include a union select to address certain known scenarios (like the null date value, 1/1/1900).</p></td>
<td><ol>
<li><p>Open the cube in SQL Server Business Intelligence Development Studio or SQL Server Data Tools.</p></li>
<li><p>Open the named query that has the join in question.</p></li>
<li><p>Add a UNION ALL SELECT clause to address the known issue. For example,</p>
<p>UNION ALLSELECT     CAST(N'' AS NVARCHAR(3)) AS NAME, 0 AS PARTITION, 0 AS RECID, 1 AS BI_ISNOTAPPLICABLE</p></li>
<li><p>ReplaceThisText</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>Change the dimension usage tab for the related cubes to remove the joins where data is in one table and not in another.</p></td>
<td><ol>
<li><p>Open the cube in SQL Server Business Intelligence Development Studio or SQL Server Data Tools.</p></li>
<li><p>Click the Dimension Usage tab.</p></li>
<li><p>Right-click the join you want to remove, and then click Delete.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Replace null values with non-null values.</p></td>
<td><p>Use integration services to create an Extract, Transform, and Load (ETL) process that takes data from your Microsoft Dynamics AX database, adds data to these key missing fields (for example, populate with the word “N/A”, “missing”, “unknown”, or “standard”) and then have your cube pull from this location.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

