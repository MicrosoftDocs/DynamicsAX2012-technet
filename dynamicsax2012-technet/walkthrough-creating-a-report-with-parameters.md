---
title: 'Walkthrough: Creating a Report with Parameters'
TOCTitle: 'Walkthrough: Creating a Report with Parameters'
ms:assetid: b98016f4-544a-452d-9a05-ce46577a5eec
ms:mtpsurl: https://technet.microsoft.com/library/Cc636713(v=AX.60)
ms:contentKeyID: 28119573
author: tonyafehr
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Creating a Report with Parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you will create a report that displays customer data. You will add parameters to the report to allow users to filter the data that displays in the report.

This walkthrough illustrates the following tasks:

  - Defining a query

  - Creating a reporting project

  - Creating a report

  - Adding parameters to a report

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX with sample data
    

    > [!NOTE]
    > <P>This walkthrough uses the CustTable table. In order to view data in the report, this table must contain data.</P>



  - Microsoft Visual Studio 2010

  - Microsoft Visual Studio tools for Microsoft Dynamics AX

## Defining a Query

There are several ways to retrieve data for reports. In this walkthrough, you will use a query that is defined within the Microsoft Dynamics AX development workspace. The following procedure explains how to define the query that will retrieve data for the report.

### To define a query

1.  Open the Microsoft Dynamics AX development workspace.

2.  In the AOT, right-click the **Queries** node, and then click **New Query**.

3.  Right-click the node for the query, click **Rename**, and then type CustomerList.

4.  Expand the node for the CustomerList query.

5.  In the AOT, right-click the **Data Dictionary** node, and then click **Open New Window**.

6.  In the new window, expand the **Tables** node.

7.  Locate the **CustTable** table and drag it onto the **Data Sources** node for the CustomerList query.

8.  Expand the **CustomerList** \> **Data Sources** \> **CustTable\_1** and then click **Fields**. In the Properties window, set the **Dynamic** property to **Yes**.

9.  Save the query.

## Creating a Reporting Project

Next, you will create a reporting project in Microsoft Visual Studio. In this walkthrough, you will use the Report Model template.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New**, and then click **Project**. The **New Project** dialog box displays.

3.  In the **Installed Templates** pane, click the **Microsoft Dynamics AX** node, and in the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type **SampleCustomerListReport**, and in the **Location** box, type a location.

5.  Click **OK**.

## Creating a Report

Now that you have created a reporting project, you are ready to create the report. The following procedure explains how to create the report.

### To create a report

1.  In Solution Editor, right-click the **SampleCustomerListReport** project, point to **Add**, and then click **Report**.

2.  In Model Editor, edit the **Name** property for the report and type CustomerList.

3.  Right-click the **Datasets** node, and then click **Add Dataset**.

4.  Select the node for the dataset.

5.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>Data Source</strong></p></td>
    <td><p><strong>Dynamics AX</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Query</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Layout</strong></p></td>
    <td><p><strong>Table</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><p><strong>False</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Customers</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><ol>
    <li><p>Click the ellipsis button (…). A dialog box displays where you can select a query that is defined in the AOT and identify the fields that you want to use.</p></li>
    <li><p>Select the <strong>CustomerList</strong> query and then click <strong>Next</strong>.</p></li>
    <li><p>In the <strong>Select Fields</strong> tab, expand the <strong>All Fields</strong> node and then select the <strong>AccountNum</strong> field.</p></li>
    <li><p>Expand the <strong>All Display Methods</strong> node and select the <strong>address</strong>, <strong>name</strong>, <strong>phone</strong> and <strong>telefax</strong> methods.</p></li>
    <li><p>Click <strong>OK</strong>.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


6.  In Model Editor, select the **Customers** node and drag it onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.

7.  Select the **AutoDesign1** node.

8.  In the **Properties** window, set the **LayoutTemplate** property to **ReportLayoutStyleTemplate**. Also, type Customer list for the **Title** property.

9.  In Model Editor, expand the **AutoDesign1** node, and then select the **CustomersTable** node for the table data region.

10. In the **Properties** window, set the **Style Template** property to **TableStyleTemplate**.

## Adding Parameters to a Report

Next, you will add parameters to the report. First, you will add a parameter and a filter that uses the parameter to allow users to select a customer for which to display data. Then, you will add parameters that will be used to determine whether to display the phone and fax numbers for the customers in the report. The following procedures explain how to define the parameters for the report.

### To add a parameter and filter for selecting customers

1.  In Model Editor, right-click the **Parameters** node for the report, point to **Add**, and then click **Parameter**.

2.  Select the node for the parameter.

3.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>Multi Value</strong></p></td>
    <td><p><strong>False</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>CustomerName</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Prompt String</strong></p></td>
    <td><p>Customers:</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Values</strong></p></td>
    <td><p>Click the ellipsis button (...). In the dialog box that displays, click the <strong>From dataset</strong> radio button. Select <strong>Customers</strong> from the drop-down for <strong>Dataset</strong>. Select <strong>name</strong> from the drop-down menu for <strong>Value field</strong>, and select <strong>name</strong> from the drop-down menu for <strong>Label Field</strong>. Click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


4.  Expand the **AutoDesign1** node, and then expand the **CustomersTable** node.

5.  Right-click the **Filters** node, and then click **Add Filter**.

6.  Select the node for the filter. The filter is going to restrict the data for the report to the records from the **Customers** dataset where the value from the name() method matches the name supplied for the **CustomerName** parameter.

7.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>Expression</strong></p></td>
    <td><p>In the drop-down, select =Fields!name.Value.</p>
    <p>The <strong>Expression</strong> is indicating what value is coming from the dataset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>SelectCustomers</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Operator</strong></p></td>
    <td><p><strong>In</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value</strong></p></td>
    <td><p>=Parameters!CustomerName.Value</p>
    <p>Value is the value that the user is supplying through the parameter.</p></td>
    </tr>
    </tbody>
    </table>


8.  To preview the report, right-click the **AutoDesign1** node in Model Editor, and then click **Preview**. The parameter that you defined displays in the **Parameters** tab.

9.  To use the parameter, select a customer name from the list that displays for the parameter, and then click the **Report** tab. The data for the selected customer displays.

10. Close the **Preview** window

### To add parameters that determine whether to display phone and fax numbers

1.  In Model Editor, right-click the **Parameters** node, point to **Add**, and then click **Parameter**.

2.  Select the node for the parameter.

3.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>Data Type</strong></p></td>
    <td><p>Boolean</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>DisplayPhoneNumber</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Prompt String</strong></p></td>
    <td><p>Display phone number?</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Values</strong></p></td>
    <td><ol>
    <li><p>Click the ellipsis button (...).</p></li>
    <li><p>In the dialog box that displays, click the <strong>Non-queried</strong> radio button.</p></li>
    <li><p>In the first row in the table, type True in the <strong>Value</strong> column and type Yes in the <strong>Label</strong> column.</p></li>
    <li><p>In the second row, type False in the <strong>Value</strong> column and type No in the <strong>Label</strong> column.</p></li>
    <li><p>Click <strong>OK</strong>.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


4.  In Model Editor, right-click the **Parameters** node, point to **Add**, and then click **Parameter**.

5.  Select the node for the parameter.

6.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>Data Type</strong></p></td>
    <td><p>Boolean</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>DisplayTeleFaxNumber</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Prompt String</strong></p></td>
    <td><p>Display fax number?</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Values</strong></p></td>
    <td><p>Click the ellipsis button (...). In the dialog box that displays, click the <strong>Non-queried</strong> radio button. In the first row in the table, type True in the <strong>Value</strong> column and type Yes in the <strong>Label</strong> column. In the second row, type False in the <strong>Value</strong> column and type No in the <strong>Label</strong> column. Click <strong>OK</strong>.</p></td>
    </tr>
    </tbody>
    </table>


7.  In Model Editor, expand the **AutoDesign1** \> **CustomersTable** \> **Data** node.

8.  Select the **phone** field, and type the expression =IIf(Parameters\!DisplayPhoneNumber.Value=True, True, False) for the **Visible** property in the **Properties** window.

9.  Select the **telefax** field, and type the expression =IIf(Parameters\!DisplayTeleFaxNumber.Value=True, True, False) for the **Visible** property in the **Properties** window.

10. To preview the report, right-click the **AutoDesign1** node in Model Editor, and then click **Preview**. The new parameters display in the **Parameters** window along with the previous parameter. To use the parameters, select a customer and specify **Yes** or **No** for the two display parameters. The data for the selected customers displays.

11. Close the **Preview** window.

## See also

[How to: Define a Report Parameter](how-to-define-a-report-parameter.md)

[How to: Define a Report Filter](how-to-define-a-report-filter.md)

[Controls Used to Render Report Parameters](controls-used-to-render-report-parameters.md)

