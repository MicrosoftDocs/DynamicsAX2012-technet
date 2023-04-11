---
title: 'Walkthrough: Creating a PowerPivot Data Mash-up'
TOCTitle: 'Walkthrough: Creating a PowerPivot Data Mash-up'
ms:assetid: 5dccd8a9-f734-410c-83d1-19850200339f
ms:mtpsurl: https://technet.microsoft.com/library/Dn198214(v=AX.60)
ms:contentKeyID: 53401822
author: tonyafehr
ms.date: 05/09/2014
mtps_version: v=AX.60
---

# Walkthrough: Creating a PowerPivot Data Mash-up 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use Microsoft Dynamics AX 2012 R2 and Microsoft Office Excel with PowerPivot to combine data from multiple sources for analysis. This topic demonstrates how to create a data mash-up that combines information extracted from a list page in Microsoft Dynamics AX and an OData feed that surfaces data from a Microsoft Dynamics AX query. To create the mash-up, perform the following steps:

  - Extract data from a list page into Excel.

  - Extract data from Microsoft Dynamics AX into PowerPivot by using an OData feed.

  - Create a pivot table with data from both sources.

## Prerequisites

Microsoft Dynamics AX 2012 R2

Microsoft Office SharePoint Server 2010 or above (Enterprise edition) with PowerPivot services and Power View services

Microsoft Office Excel 2010 or above with PowerPivot add-in


> [!NOTE]
> <P>For information about PowerPivot capabilities in Excel 2013, see <A href="https://office.microsoft.com/excel-help/whats-new-in-powerpivot-in-excel-2013-ha102893837.aspx">What’s new in PowerPivot in Excel 2013</A>.</P>



## Extracting Data from a List Page into Excel

The first set of data for the data mash-up is from the **All customers** list page in Microsoft Dynamics AX. You can add additional fields to the list page and then extract the data by using the **Export to Excel** button.

### To add columns to the list page

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Right-click the column header of the grid and then click **Personalize**.

3.  Expand **ListPageGrid**.

4.  Click **Add fields**.

5.  Add the following fields from the **Customers** table:
    
      - Method of Payment
    
      - Segment
    
      - Subsegment
    
      - Customer classification group

6.  Close the **Add fields** window and refresh the form.

### To extract data from the list page

  - After the **All customers** list page is refreshed, click **Export to Excel List**.

## Importing Data into PowerPivot by Using an OData Feed

The other set of data for the mash-up is from an OData feed. You can create an OData feed that exposes information from an existing Microsoft Dynamics AX query or from a custom Microsoft Dynamics AX query. After the OData query is set up, you can import the data into PowerPivot. In the following procedures, you will create an OData feed to expose data from the CustTransList query, and then import the data into PowerPivot.

### To create an OData feed

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document data sources**.

2.  Click **New**.

3.  Enter the following values:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Module</p></td>
    <td><p>Accounts receivable</p></td>
    </tr>
    <tr class="even">
    <td><p>Data source type</p></td>
    <td><p>Query reference</p></td>
    </tr>
    <tr class="odd">
    <td><p>Data source name</p></td>
    <td><p>CustTransList</p></td>
    </tr>
    <tr class="even">
    <td><p>Activated</p></td>
    <td><p>Select the <strong>Activated</strong> check box.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Description</p></td>
    <td><p>Enter a description of the feed.</p></td>
    </tr>
    </tbody>
    </table>


4.  Close the **Document data sources** form. You can test the OData feed by navigating to the following URL:
    
    http://\<ServerName\>:8101/DynamicsAX/Services/ODataQueryservice/.
    

    > [!NOTE]
    > <P>You may need to adjust the port number in the URL. 8101 is the default port number.</P>



### To import content using the OData feed

1.  In the same Excel workbook you used earlier in this walkthrough, click the **PowerPivot** tab.

2.  Click **PowerPivot window**.

3.  Click **From Data Feeds**.

4.  In **Data Feed Url**, enter http://\<ServerName\>:8101/DynamicsAX/Services/ODataQueryservice/.

5.  Click **Next**.

6.  Select **CustTransList**, and then click **Finish**.

## Creating a Pivot Table

Now that you have data from the list page and from the OData feed, you can link the data and then view it as a pivot table.

### To create a linked table

1.  In Excel, click the **PowerPivot** tab.

2.  Click **Create Linked Table**.

3.  Right-click the sheet title, and then click **Rename**. Enter Customers to rename the sheet from **Table** to **Customers**.

### To create a pivot table

1.  In PowerPivot, click **PivotTable**.

2.  Click **OK** to create a pivot table in a new sheet.
    

    > [!NOTE]
    > <P>Notice that the pivot table contains data from both sources of data: the Customers data you exported from the list page and the data from the CustTransList query that is exposed by the OData feed.</P>



3.  Expand **CustTransList** and then select **CustTrans\_AmountMST**. The total sales value is displayed in the pivot table.

4.  Expand **Customers** and then select **Segment**. The segment value is displayed in the pivot table.

5.  Click **Create** on the warning that says **Relationship may be needed**. Click **Close**.

## Next Steps

After you complete this walkthrough, you can upload a PowerPivot model (your Excel sheet) into SharePoint library, and use it to create Power View reports. For more information about creating Power View reports, see [Create a report by using Power View to connect to a cube](create-a-report-by-using-power-view-to-connect-to-a-cube.md) and [Walkthrough: Creating an Analyze Data Button on a List Page](walkthrough-creating-an-analyze-data-button-on-a-list-page.md).

## See also

[Reporting in Microsoft Dynamics AX](reporting-in-microsoft-dynamics-ax.md)

[Walkthrough: Creating an Analyze Data Button on a List Page](walkthrough-creating-an-analyze-data-button-on-a-list-page.md)

[OData Query Service](https://blogs.msdn.com/b/aif/archive/2011/08/23/odata-query-service.aspx)

  


