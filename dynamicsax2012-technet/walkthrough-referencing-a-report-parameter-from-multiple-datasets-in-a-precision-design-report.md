---
title: 'Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report'
TOCTitle: 'Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report'
ms:assetid: fbb6d395-b72b-4c74-acda-842263d970ee
ms:mtpsurl: https://technet.microsoft.com/library/Cc624720(v=AX.60)
ms:contentKeyID: 28119624
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will create a vendor invoice report. You will use SQL Report Designer to create a precision design for the report. The following illustration shows the report that you will create in this walkthrough.

![Report precision design](images/Cc624720.PrecisionDesignReport(AX.60).png "Report precision design")


> [!NOTE]
> <P>The data that displays in your report may vary depending on the sample data that is available to you.</P>



This walkthrough illustrates the following tasks:

  - Defining queries

  - Creating a reporting project

  - Creating a precision design report using SQL Report Designer

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>In this walkthrough, you will use the VendInvoiceJour and VendInvoiceTrans tables. Therefore, these tables must contain data.</P>



  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio Tools for Microsoft Dynamics AX

## Defining Queries

There are several ways to retrieve data for reports. In this walkthrough, you will create queries in the Microsoft Dynamics AX development workspace. The following procedure explains how to define the queries that will retrieve data for a vendor invoice report.

### To define the queries

1.  Open the Microsoft Dynamics AX development workspace.

2.  In the AOT, right-click the **Queries** node, and then click **New Query**.

3.  Right-click the node for the query, click **Rename**, and then type InvoiceJournal.

4.  Expand the node for the InvoiceJournal query.

5.  In the AOT, right-click the **Data Dictionary** node, and then click **Open New Window**.

6.  In the new window, expand the **Tables** node.

7.  Locate the **VendInvoiceJour** table and drag it onto the **Data Sources** node for the query.

8.  Expand the node for the **VendInvoiceJour\_1** data source.

9.  Select the **Fields** node, in the Properties window, set the **Dynamic** property to **Yes**.

10. Right-click the **Ranges** node, and then click **New Range**.

11. Right-click the **VendGroup** node and then click **Properties**, and in the **Properties** window, set the **Field** property to **InvoiceId**.

12. In the AOT, right-click the **Queries** node, and then click **New Query**.

13. Right-click the node for the query, click **Rename**, and then type InvoiceTransaction.

14. Expand the node for the InvoiceTransaction query.

15. In the AOT that is displaying the Data Dictionary node, locate the **VendInvoiceTrans** table and drag it onto the **Data Sources** node for the query.

16. Expand the node for the **VendInvoiceTrans\_1** data source.

17. Select the **Fields** node, in the Properties window, set the **Dynamic** property to **Yes**.

18. Right-click the **Ranges** node, and then click **New Range**.

19. Select the node for the range, and in the **Properties** window, set the **Field** property to **InvoiceId**.

20. Save the queries.

## Creating a Reporting Project

Next, you will create a reporting project in Microsoft Visual Studio. In this walkthrough, you will use the Report Model template.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, click **New**, and then click **Project**. The **New Project** dialog box is displayed.

3.  In the **Installed Templates** pane, click the **Microsoft Dynamics AX** node. In the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleVendorInvoiceReport, and in the **Location** box, type a location.

5.  Click **OK**.

## Creating a Precision Design Report By Using SQL Report Designer

Now that you have created a reporting project, you are ready to create a precision design report to display the data returned by the queries that you created in Microsoft Dynamics AX. To do this, you will first define datasets for the report. Then, you will configure the parameters that are created for the datasets. Finally, you will use SQL Report Designer to define the report layout.

### To define datasets for the report

1.  In Solution Explorer, rick-click the **SampleVendorInvoiceReport** project, point to **Add**, and then click **Report**.

2.  In Model Editor, right-click the **Report1** node, and then click **Rename**.

3.  Type VendorInvoiceReport.

4.  Right-click the **Datasets** node for the report, and then click **Add Dataset**.

5.  Select the node for the dataset.

6.  In the **Properties** window, specify the following property values.
    
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
    <td><p>Dynamic Filters</p></td>
    <td><p>False</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source</strong></p></td>
    <td><p><strong>Dynamics AX</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>InvoiceJournalDataset</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays where you can select a query that is defined in the AOT and identify the fields that you want to use. Select the <strong>InvoiceJournal</strong> query, click <strong>Next</strong>, and then expand the <strong>All Fields</strong> node. Select the <strong>PurchId</strong>, <strong>OrderAccount</strong>, <strong>InvoiceAccount</strong>, <strong>InvoiceId</strong>, <strong>InvoiceDate</strong>, and <strong>DueDate</strong> fields. Click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


7.  In Model Editor, right-click the **Datasets** node for the report, and then click **Add Dataset**.

8.  Select the node for the dataset.

9.  In the **Properties** window, specify the following property values.
    
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
    <td><p>Dynamic Filters</p></td>
    <td><p>False</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source</strong></p></td>
    <td><p><strong>Dynamics AX</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>InvoiceTransactionDataset</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays where you can select a query that is defined in the AOT and identify the fields that you want to use. Select the <strong>InvoiceTransaction</strong> query, click <strong>Next</strong>, and then expand the <strong>All Fields</strong> node. Select the <strong>ItemId</strong>, <strong>Name</strong>, <strong>Qty</strong>, <strong>PurchPrice</strong>, and <strong>LineAmount</strong> fields. Click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>
    
    The queries that are used for both of the datasets have a range based on the InvoiceId field. Because this range exists, dataset and report parameters are added to the report in Model Editor. The following table describes dataset and report parameters.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Parameter</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Dataset parameter</p></td>
    <td><p>Dataset parameters are generated when a dataset is based on the <strong>Query</strong> property and the <strong>Dynamic Filters</strong> property of the dataset.</p>
    <ul>
    <li><p>When you define a dataset where the <strong>Dynamic Filters</strong> property is set to <strong>True</strong>, a single dataset parameter is created to transport the dynamic filters that are set at runtime for the report.</p></li>
    <li><p>When the <strong>Dynamic Filters</strong> property is set to <strong>False</strong>, zero to many parameters are created based on the <strong>Query</strong> property of the dataset.</p></li>
    </ul>
    <p></p></td>
    </tr>
    <tr class="even">
    <td><p>Report parameter</p></td>
    <td><p>Report parameters are defined globally for the report. They are generated when the report query includes parameters, or they can be created manually. After a report parameter is created, you must set properties that identify it and that control how it is used in the report. The naming convention of report parameters the DatasetName_FieldName.</p></td>
    </tr>
    </tbody>
    </table>
    
    Parameters of this kind are added when you bind the query to a dataset. In this example, both report parameters represent the same field. Therefore, you will set up the report to use one of the report parameters as a design parameter and both of the dataset parameters for the InvoiceID field will reference the design parameter.

### To configure the parameters

1.  In Model Editor, expand the **Parameters** node for the report.

2.  Select the **InvoiceJournalDataset\_InvoiceId** parameter.

3.  In the **Properties** window, type Invoice ID: for the **Prompt String** property.

4.  Right-click the **InvoiceTransactionDataset\_InvoiceId** parameter and then click **Delete**.

5.  Expand **Datasets** \> **InvoiceTransactionDataset** \> **Parameters**, and then select **InvoiceID**. In the Properties window, set the **Report parameter** to **InvoiceJournalDataset\_InvoiceId**. Now both InvoiceID dataset parameters are set to **InvoiceJournalDataset\_InvoiceId**.

After the datasets and parameters are defined, you can start defining the report layout. You create a report layout by dragging and dropping data regions, text boxes, images, and other items that you want to include in your report to the design surface.

### To define a precision design by using SQL Report Designer

1.  In Model Editor, right-click the **Designs** node for the report, point to **Add**, and then click **Precision Design**.

2.  Right-click the new **PrecisionDesign1** node and choose **Edit Using Designer**.
    
    The **Precision Design** window is displayed with an empty report. The **Report Data** window that contains the datasets that you defined in the model appears on the left.

3.  In the **Toolbox** pane, click the **Table** element and drag it to the design surface. Report Designer draws a table data region with three columns.
    

    > [!NOTE]
    > <P>The <STRONG>Toolbox</STRONG> may appear as a tab on the left side of the <STRONG>Report Data</STRONG> pane. If the <STRONG>Toolbox</STRONG> is not visible, from the <STRONG>View</STRONG> menu, click <STRONG>Toolbox</STRONG>.</P>



4.  From the **Report Data** pane, drag the PurchId field to the first column in the table.
    
    When you drop the field into the first column, two things occur. First, the data cell will display the field name, known as the field expression, in brackets: \[PurchId\]. Second, a column header value is automatically added to Header row, just above the field expression. By default, the column is the name of the field. You can select the Header row text and type a new name.

5.  Press Ctrl-S to save the design.

6.  Click the **Design** tab.

7.  Right-click the table, point to **Insert Column**, and then click **Right**. Repeat this until there are five columns in the table.

8.  Drag the **OrderAccount**, **InvoiceAccount**, **InvoiceDate**, and **DueDate** to the columns of the table on the design surface.

9.  In the **Toolbox** pane, select the **Table** element, and drag it below the previous table.

10. Right-click the table, point to **Insert Column**, and then click **Right**. Repeat this until there are five columns in the table.

11. Drag the **ItemId**, **Name**, **Qty**, **PurchPrice**, and **LineAmount** fields from **InvoiceTransactionDataset** in the **Report Data** window to the columns that you created. The following diagram shows the two table data regions that have been populated with fields.
    
    ![Precision design screenshot](images/Cc624720.PrecisionDesignTables(AX.60).png "Precision design screenshot")

12. Save the report.

13. To preview the report design, click the **Preview** tab in SQL Report Designer. Type an invoice ID in the **Parameters** tab, and then click the **Report** tab to view the report.
    

    > [!NOTE]
    > <P>To find a vendor invoice number in the data you are using, use the Open Vendor Invoices list. In Microsoft Dynamics AX, go to <STRONG>Accounts payable</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Vendor invoices</STRONG> &gt; <STRONG>Open vendor invoices</STRONG>. You can also use the * wildcard in the invoice ID parameter.</P>



You have successfully added a Table data region to your report, added fields to the data region, and previewed your report. In the next section, you will format the report.

### To format the report by using SQL Report Designer

1.  Click the **Design** tab.

2.  In the **Toolbox** pane, select the **Text Box** element and drag it to the upper-left side of the report.

3.  Right-click the text box and then click **Text Box Properties**.

4.  In the **Value:** field, type Invoice specification.

5.  Click **Font**, in the **Font** field, select **Tahoma**.

6.  In the **Size** field, select **14pt**.

7.  Click **OK**. You may need to adjust the size of the text box.

8.  In the **Toolbox** pane, select the **Line** element and draw a line below the text box that you added in the previous step.

9.  Select the line, and in the **Properties** window, set the **LineWidth** property to **2pt** and set **LineColor** property to **Blue**.

10. In the first table, right-click the \[InvoiceDate\] field expression and then click **Text Box Properties**.

11. Click **Number**, and then in the **Category** field, select **Date**.

12. In the **Type** box, select **January 31, 2000**.

13. Click **OK**.

14. In the first table, right-click the \[DueDate\] field expression and repeat the previous steps to format the date.

15. In the first table, click the row handle for the first row to select the field headers, in the **Properties** window, expand the **Font** property and set the **FontFamily** to **Tahoma** and the **FontWeight** to **Bold**.

16. In the first table, click the row handle for the second row to select the field expressions, in the **Properties** window, expand the **Font** property and set the **FontFamily** to **Tahoma**.

17. In the second table, click the row handle for the first row to select the field headers, in the **Properties** window, expand the **Font** property and set the **FontFamily** to **Tahoma** and the **FontStyle** to **Italic**.

18. In the second table, click the row handle for the second row to select the field expressions in the second row, in the **Properties** window, expand the **Font** property and set the **FontFamily** to **Tahoma**.

19. In the first table, select the \[OrderAccount\] field expression, in the **Properties** window, expand the **Size** property, and then set the **Width** to **2in**.

20. In the second table, select the \[Name\] field expression, in the **Properties** window, expand the **Size** property, and then set the **Width** to **2in**.

21. Select the second table, and in the **Properties** window, set the **BackgroundColor** to **Lavender**.

22. In the second table, right-click a cell in the first row, point to **Insert Row**, and then click **Above**.

23. In the new row, select the fields, right-click the selection, and then click **Merge Cells**.

24. Select the merged cell, and in the **Properties** window, set the **Font** property to **Tahoma, 10pt, Default, Bold, Default**, set the **TextAlign** property to **Center**, and in the field type Item details.

25. Select the \[PurchPrice\] and the \[LineAmount\], and in the **Properties** window, type c for the **Format** field. This will format the values in these cells as currency.

You have successfully formatted your report. In the next section, you will add totals to the report.

### To add totals to the report by using Report Designer

1.  In the second table, right-click the second row, point to **Row Group**, click **Delete Group**, select the **Delete group only**, and then click **OK**.

2.  Add two rows to the table. To do this, right-click a cell in the last row of the table, point to **Insert Row**, and then click **Below**.

3.  In the first added row, select the first four cells, right-click the selected cells and then click **Merge Cells**.

4.  Select the merged cell and type Sales tax:. In the **Properties** window, set the **TextAlign** property to **Right**.

5.  Right-click the last cell in the first footer row and choose **Expression**. Set the **Expression**, type =Sum(Fields\!LineAmount.Value\*.07).

6.  In the Properties window, set the **Format** property to c.

7.  In the last footer row, merge the first four cells and type Total amount due:.

8.  Select the merged cell, and in the **Properties** window, set the **FontWeight** property to **Bold**, and set the **TextAlign** property to **Right**.

9.  Select the last cell in the last footer row, type =Sum(Fields\!LineAmount.Value\*1.07) for the **Value** field, set the **FontWeight** property to **Bold**, and type c for the **Format** property.

10. Select the cells that display the values for sales tax and total amount due, and in the **Properties** window, set the **BorderColor** property to **DimGrey**.

11. Save and preview the report.

You have now successfully created a precision design report by using the Microsoft Dynamics AX tools for Visual Studio and Report Designer. You can now [create a menu item](how-to-create-a-menu-item-for-a-report.md) to display the report in the Microsoft Dynamics AX client.

## See also

[Creating Reports Overview](creating-reports-overview.md)

[How to: Create a Precision Design for a Report](how-to-create-a-precision-design-for-a-report.md)

[Walkthrough: Creating an Auto Design Report](walkthrough-creating-an-auto-design-report.md)

[Designing Reports in Report Designer](http://go.microsoft.com/fwlink/?linkid=229038)

