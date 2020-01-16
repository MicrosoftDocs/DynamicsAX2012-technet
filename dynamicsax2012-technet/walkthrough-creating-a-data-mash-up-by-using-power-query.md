---
title: 'Walkthrough: Creating a data mash-up by using Power Query'
TOCTitle: 'Walkthrough: Creating a data mash-up by using Power Query'
ms:assetid: 31955256-2478-45f2-a48a-474c0a3fb7ff
ms:mtpsurl: https://technet.microsoft.com/library/Dn768211(v=AX.60)
ms:contentKeyID: 62497508
author: Khairunj
ms.date: 04/01/2015
mtps_version: v=AX.60
---

# Walkthrough: Creating a data mash-up by using Power Query 


You can use Microsoft Office Excel to analyze data from Microsoft Dynamics AX. You can use tools that are included in Power BI for Office 365 to incorporate data from a variety of data sources from outside Microsoft Dynamics AX for deeper analysis.

In this walkthrough, you will use an OData feed to get Microsoft Dynamics AX data into Excel, and then mash that data with population data from Wikipedia to create a Power View report to gain business insights. Then you can share the report with your organization by using Power BI sites.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn768211.TopicIcons_Walkthrough(AX.60).png" title="Walkthrough" alt="Walkthrough" />
<p>Prerequisites</p>
<p>1. Create an OData feed</p>
<p>2. Import the OData feed into Excel</p>
<p>3. Import external data</p>
<p>4. Merge the data</p>
<p>5. Create a calculated column</p>
<p>6. Create a Power View chart</p>
<p>7. Share the report in Power BI sites</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p>
<p><a href="microsoft-dynamics-ax-integration-with-power-bi-for-office-365.md">Microsoft Dynamics AX integration with Power BI for Office 365</a></p></td>
</tr>
</tbody>
</table>


## Prerequisites

Before you can complete the procedures in this topic, you must make sure that the following prerequisites are in place.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required software</p></td>
<td><p>This walkthrough utilizes Power Query, Power Pivot, and Power BI Sites from Power BI for Office 365</p></td>
<td><p><a href="http://www.microsoft.com/en-us/powerbi/default.aspx">Power BI for Office 365</a></p></td>
</tr>
</tbody>
</table>


## 1\. Create an OData feed

The **Queries** node in the AOT has a large collection of pre-built views that you can use to expose data via OData feeds. In this walkthrough, you will use an OData feed based on the custom query CustomerInvoiceLinesTVsonly, which is based on the CustInvoiceSRS query. If your Microsoft Dynamics AX installation already has the document data source based on the CustomerInvoiceLinesTVsonly query, you can skip this procedure.

1.  In Microsoft Dynamics AX, click **Organization administration** \> **Setup** \> **Document management** \> **Document data sources**.

2.  Click **New**.

3.  Specify the following values for the new data source:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
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
    <td><p>Custom query</p></td>
    </tr>
    <tr class="odd">
    <td><p>Data source name</p></td>
    <td><p>CustInvoiceSRS</p>
    <p>After you enter CustInvoiceSRS, the <strong>Edit query</strong> window will appear. In Range, click <strong>Add</strong>. In Table, enter <strong>Customer invoice lines</strong>. In Derived table, enter <strong>Customer invoice lines</strong>. In Field, enter <strong>Item</strong>. In Criteria, enter T0004, T005.</p>
    <p>For the Date field, in Criteria, enter “1/1/2012”..”12/31/2012”.</p>
    <p>Click <strong>OK</strong> to close the <strong>CustInvoiceSRS</strong> Edit query form.</p>
    <p>Rename the data source to CustomerInvoiceLinesTVsOnly.</p></td>
    </tr>
    <tr class="even">
    <td><p>Activated</p></td>
    <td><p>Select the <strong>Activated</strong> check box.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Description</p></td>
    <td><p>Custom query based on CustInvoiceSRS.</p></td>
    </tr>
    </tbody>
    </table>


4.  Click **Close** to close the Document data sources form.

Back to top

## 2\. Import the OData feed into Excel

You can use Excel to consume OData feeds. Power Query is a Power BI for Office 365 component in Excel that helps you discover data that you can import into Excel for modeling purposes. First, you will import Microsoft Dynamics AX data from an OData feed and import only the required data.

1.  In Excel, click **POWER QUERY** \> **From Other Sources** \> **From OData Feed**.
    

    > [!NOTE]
    > <P>You can install Power Query from <A href="https://office.microsoft.com/excel/download-microsoft-power-query-for-excel-fx104018616.aspx">here</A>.</P>



2.  Enter the URL of the OData feed you created in the previous procedure. If you are prompted for credentials, select **Windows** and continue. The URL is in the following format:
    
        http://<ServerName>:8101/DynamicsAx/Services/ODataQueryService/
    

    > [!NOTE]
    > <P>Note the following:</P>
    > <UL>
    > <LI>
    > <P>The letters in the URL must be capitalized as shown above. The case is important for PowerBI refresh through the Data Management Gateway.</P>
    > <LI>
    > <P>If you open the query service URL in a browser, you will see XML that shows a list of the OData feeds that are available.</P></LI></UL>



3.  In Navigator, double click **CustomerInvoiceLinesTVsOnly**. If you are prompted to select privacy levels, specify your desired privacy level. For this walkthrough, select **Public**.

4.  Filter the data before importing it.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Task</p></th>
    <th><p>Instructions</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Isolate transactions in US Dollars</p></td>
    <td><p>Click the <strong>CustInvoiceJour_CurrencyCode</strong> column drop-down and select only <strong>USD</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p>Remove the transactions that are not subject to tax</p></td>
    <td><p>Click the <strong>CustInvoiceTrans_TaxGroup</strong> column drop-down and clear <strong>No-Tax</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Remove columns that aren’t needed</p></td>
    <td><p>Select the <strong>CustInvoiceTrans_TaxGroup</strong> and <strong>CustInvoiceTrans_LineAmount</strong> columns. Right-click the selection and then click <strong>Remove Other Columns</strong>.</p></td>
    </tr>
    </tbody>
    </table>


5.  Click **Apply & Close**.

Back to top

## 3\. Import external data

Next, you will import external data that you will use to add additional context to the Microsoft Dynamics AX data.

1.  In Excel, click **POWER QUERY** \> **Online Search**.

2.  In the **Online Search** pane, enter US population by state, and then press Enter.

3.  Point to the Wikipedia entry called **States and territories – List of U S states and territories by population**, and then click **Edit**.

4.  Select the **State or territory** and **Population estimate for July 1, 2013** columns. Right-click the selected columns and then click **Remove Other Columns**.

5.  Right-click **Population estimate for July 1, 2013** and then click **Rename**. Enter Population.

6.  Right-click **Population**, point to **Change Type**, and then click **Number**.

7.  Click **Apply & Close**. The data is added to your workbook in a new tab.

8.  Click **POWER QUERY** \> **Online Search**.

9.  In the **Online Search** pane, enter US state abbreviations, and then press Enter.

10. Point to the Wikipedia entry called **Table listing U S state abbreviations**, and then click **Edit**.

11. Select the **Region\_0** and **Codes\_1** columns. Right-click the selection, and then click **Remove Other Columns**.

12. Click **Apply & Close**. The data is added to your workbook in a new tab.

Back to top

## 4\. Merge the data

You now have data in three tabs. One contains the tax group (state abbreviation) and customer invoice transaction line amount from Microsoft Dynamics AX, one contains the population by state from Wikipedia, and one contains the states and abbreviations. Next you will merge the data so that you can work with all of it in one tab.

1.  Click **POWER QUERY** \> **Merge**.

2.  Select **CustomerInvoiceLinesTVsOnly** from the first drop-down list.

3.  Select **Table listing U S state abbreviations** from the second drop-down list.

4.  Select the **CustInvoiceTrans\_TaxGroup** column from the first source and the **Codes\_1** column from the second source to specify the column to use to join the two sources, and then click **OK**. If you are prompted to select a privacy level, select **Public**.

5.  Click the drop-down in **NewColumn** and select **Region\_0**. **Codes\_1** represents the state abbreviation and is already a column in the spreadsheet, so you don’t need to add it a second time.

6.  Edit the column names:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Column name</p></th>
    <th><p>Rename to</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>CustInvoiceTrans_TaxGroup</p></td>
    <td><p>StateCode</p></td>
    </tr>
    <tr class="even">
    <td><p>CustInvoiceTrans_LineAmount</p></td>
    <td><p>LineAmount</p></td>
    </tr>
    <tr class="odd">
    <td><p>NewColumn.Region_0</p></td>
    <td><p>State</p></td>
    </tr>
    </tbody>
    </table>


7.  Click **Apply & Close**. The merged data is added to your workbook in a new tab.

8.  Click **POWER QUERY** \> **Merge**.

9.  Select **Merge1** from the first drop-down list.

10. Select **States and territories – List of U S states and territories by population** from the second drop-down list.

11. Select the **State** column from the first source and the **State or territory** column from the second source to specify the column to use to join the two sources, and then click **OK**. If you are prompted to select a privacy level, select **Public**.

12. Click the drop-down in **NewColumn** and select **Population**. **State or territory** represents the state and is already a column in the spreadsheet, so you don’t need to add it a second time.

13. Right-click **NewColumn.Population**, and then click **Rename**. Enter Population for the new name.

14. Click **Apply & Close**. The merged data is added to your workbook in a new tab.

Back to top

## 5\. Create a calculated column

You can use the Query Editor to add a calculated column that calculates the sales per capita.

1.  Click **POWER QUERY**. In the **Workbook Queries** pane, double-click **Merge2**. The Query Editor opens.

2.  Click **Insert** \> **Insert Custom Column**.

3.  In **New column name**, enter Sales per capita.

4.  In Custom column formula, enter the following and then click **OK**:
    
        100*([LineAmount]/[Population])

5.  Click **Home** \< **Apply & Close**. The merged data is added to your workbook in a new tab.

Back to top

## 6\. Create a Power View chart

Now that you have merged Microsoft Dynamics AX data with population data from Wikipedia and incorporated a calculated column that uses both data sources, you can use Power View to create a chart to gain business insights.

1.  In Excel, click **INSERT** \> **Power View**.

2.  In the **Power View Fields** pane, expand **Merge2**.

3.  Select **StateCode**, **LineAmount**, and **Population**.

4.  In **FIELDS**, in the drop-down for **Population**, select **Average**.

5.  Click **Design** \> **Other Chart** \> **Scatter**. Resize the scatter chart to make it bigger.

6.  In the **Power View Fields** pane, expand **Merge2**. In the drop-down for **Sales per capita**, select **Add as Size**.

7.  Save your workbook.

Back to top

## 7\. Share the report in Power BI sites

Now that you’ve created the report, you can add it to your Power BI sites page and share it with other people. You can also access your reports by using the Power BI app from the Windows store app. For more information about Power BI sites, see the [Power BI sites documentation](http://www.microsoft.com/en-us/powerbi/home/share-collaborate.aspx). For more information about the Power BI Windows Store app, see [Power BI Windows Store help](https://office.microsoft.com/office365-sharepoint-online-enterprise-help/power-bi-windows-store-app-help-ha104010871.aspx?ctt=5%26origin=ha104095851).

1.  From your Power BI sites page, click **Shared with Everyone**.

2.  Click **add** and then click **Upload file**.

3.  In **Choose a file**, enter the path of the Excel workbook you created and then click **OK**.

4.  Click the ellipses (…) on the report. You can add the report to your favorites, feature the report, make it available in Power Q\&A, schedule a data refresh, or edit the report.

5.  Click the chart. The chart opens in the web browser. You can share the report by sending the URL that is in the browser with other people who have access to it.

Back to top

  


