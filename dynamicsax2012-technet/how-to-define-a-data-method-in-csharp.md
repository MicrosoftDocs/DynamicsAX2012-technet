---
title: 'How to: Define a Data Method in C#'
TOCTitle: 'How to: Define a Data Method in C#'
ms:assetid: b96b3a08-89c1-47bf-a388-acf066efd6df
ms:mtpsurl: https://technet.microsoft.com/library/Cc636690(v=AX.60)
ms:contentKeyID: 28119572
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# How to: Define a Data Method in C\# 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can provide code for a data method by using C\# or Visual Basic. The default template that is used for a data method is provided in C\#. This topic describes the steps to define a report data method in C\#. You can use a data method for advanced scenarios to retrieve and manipulate the data that displays in your reports. For example, you can use a data method to access a data source other than Microsoft Dynamics AX, to do special formatting, to set specific color schemes for charts, or to generate the URL target for a custom drill through navigation on a report.

### To define a data method in C\#

1.  In Visual Studio, from the **File** menu, point to **New** and then click **Project**.

2.  In the **New Project** window, click the **Microsoft Dynamics AX** installed template and then click the **Report Model** template.

3.  Give the reporting project a name and then click **OK**.

4.  In Solution Explorer, right-click the reporting project, point to **Add**, and then click **Report**.

5.  In Model Editor, right-click the **Data Methods** node, and then click **Add Data Method**.

6.  Right-click the node for the data method, and then click **View Code**. The default template that is used for a data method is provided in C\#. In Solution Explorer, a business logic project is added to the solution with a code file that has a name in the form \<ReportName\>.cs. In code editor, the code for the data method displays in a class that has the same name as the report. The following template is provided for a data method:
    
    ``` csharp
    [DataMethod(),PermissionSet(SecurityAction.Assert, Name = "FullTrust")]
    public static string DataMethod1()
    {
        throw new NotImplementedException("The method or operation is not implemented.");
    }
    ```
    
    In order to use a data method as a source of data for a report dataset, it must return an IEnumerable\<DataRow\> or DataTable instance. When you are using large data sets, we recommend that you return an IEnumerable\<DataRow\> instance and use a yield return statement because it is more efficient than returning a DataTable instance. Be aware of the amount of data you are returning from the data method because large amounts of data will negatively affect report performance.When a data method is bound to a dataset, dataset parameters are created for each parameter in the data method. Parameters display on the report to allow the end-user to filter data. For more information about parameters for datasets, see [Parameters Overview](parameters-overview.md).

7.  In the code for the data method, rename the data method and specify an appropriate return value.

8.  Remove the line of code for the exception that states the data method is not implemented, and then add your code to the method. The following code example returns a single row of data at a time using an IEnumerable\<DataRow\> instance. This data method can be used when creating a report data set. The following example shows a data method that creates and returns inventory data for a single row of data at a time. In an actual application, the code in the data method would retrieve the data from some other source and return it one row at a time.
    
    ``` csharp
    [DataMethod(), PermissionSet(SecurityAction.Assert, Name = "FullTrust")]
    public static IEnumerable<DataRow> CreateInventoryItemByRow()
    {
        // Define a data table.
        DataTable table = new DataTable();
        table.Columns.Add(new DataColumn("ItemID", Type.GetType("System.Int32")));
        table.Columns.Add(new DataColumn("Name", Type.GetType("System.String")));
        table.Columns.Add(new DataColumn("Description", Type.GetType("System.String")));
        table.Columns.Add(new DataColumn("Cost", Type.GetType("System.Decimal")));
        table.Columns.Add(new DataColumn("SellingPrice", Type.GetType("System.Decimal")));
    
        DataRow row = null;
        row = table.NewRow();
        row.ItemArray = new object[] { 1734, "Clamp", "Workbench Clamp", 12.48, 17.99 };
        yield return row;
    
        row = table.NewRow();
        row.ItemArray = new object[] { 1983, "Saw", "Wooden Handle Saw", 7.89, 11.99 };
        yield return row;
    
        row = table.NewRow();
        row.ItemArray = new object[] { 6728, "Screwdriver", "Standard Screwdriver", 2.75, 3.99 };
        yield return row;
    
        row = table.NewRow();
        row.ItemArray = new object[] { 4920, "Nails", "Roofing Nails 5lbs", 12.45, 15.99 };
        yield return row;
    
        row = table.NewRow();
        row.ItemArray = new object[] { 4829, "Tape Measure", "25 ft Tape Measure", 12.87, 16.99 };
        yield return row;
    
        row = table.NewRow();
        row.ItemArray = new object[] { 2893, "Nails", "Finish Nails", 3.90, 5.99 };
        yield return row;
    }
    ```

9.  To build the project, in Solution Explorer right-click the solution that contains the business logic project, and then click **Build**. Building the solution ensures that the report model and the code are in sync. The name of the data method and all other properties that you defined in the code are now reflected in Model Editor. The name of the data method, parameters, and all other properties that you defined in the code are now reflected in Model Editor.

The next step is to [bind a dataset to the data method](how-to-bind-a-dataset-to-a-data-method.md) as a source of report data or [invoke the data method by using an expression](how-to-use-a-data-method-in-an-expression.md).

## See also

[Report Data Method Overview](report-data-method-overview.md)

[How to: Define a Data Method in Visual Basic](how-to-define-a-data-method-in-visual-basic.md)

