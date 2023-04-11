---
title: 'How to: Define a Data Method in Visual Basic'
TOCTitle: 'How to: Define a Data Method in Visual Basic'
ms:assetid: 78eea42c-e9f9-43a1-a2b8-7cc8bf3eb571
ms:mtpsurl: https://technet.microsoft.com/library/Hh538449(v=AX.60)
ms:contentKeyID: 39508873
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- vb
---

# How to: Define a Data Method in Visual Basic 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can provide code for a data method by using C\# or Visual Basic. The default template that is used for a data method is provided in C\#. This topic describes the steps to define a report data method in Visual Basic. To change the template that is used for a data method to Visual Basic, you must set the **Data Method Library** property of the report to a Visual Basic project. You can use a data method for advanced scenarios to retrieve and manipulate the data that displays in your reports. For example, you can use a data method to access a data source other than Microsoft Dynamics AX, to do special formatting, to set specific color schemes for charts, or to generate the URL target for a custom drill through navigation on a report.

### To define a data method in Visual Basic

1.  In Visual Studio, from the **File** menu, point to **New** and then click **Project**.

2.  In the **New Project** window, click the **Microsoft Dynamics AX** installed template and then click the **Report Model** template.

3.  Give the reporting project a name and then click **OK**.

4.  In Solution Explorer, right-click the solution, point to **Add**, and then click **New Project**.

5.  In the **Add New Project** window, in the **Installed Templates** area, click **Visual Basic**, and then click the **Class Library** template. Give the project the same name as the report you are defining the data method for.

6.  In the **Add New Project** toolbar, click the **.NET Framework** drop-down list and then click **.NET Framework 3.5**. Reporting Services does not support .NET Framework 4.

7.  Click **OK**. The Visual Basic project template adds a class named Class1 in the class1.vb file. You have the option to delete the Class1 class.

8.  In Solution Explorer, right-click the Visual Basic project, and then click **Properties**. In the **Application** area, delete the text in the **Root namespace** field.

9.  In Solution Explorer, right-click the Visual Basic project and then click **Add \<ProjectName\> to AOT**. This also builds the solution.

10. Right-click the report project, point to **Add**, and then click **Report**. A report is added with a name like **Report1**.

11. In Model Editor, select the report, such as **Report1**. In the Properties window, click the **Data Method Library** drop-down and then click the Visual Basic project that you added to the AOT in the previous steps. The list contains the business logic projects that have been built and added to the AOT.

12. In Model Editor, right-click the **Data Methods** node, and then click **Add Data Method**.

13. Give the data method a new name. For the following example, type **GetCustomerData**.

14. Right-click the node for the data method, and then click **View Code**. Because you set the data method library to a Visual Basic project, the template that is used for the data method is provided in Visual Basic. In Solution Explorer, a business logic project is added to the solution with a code file that has a name in the form \<ReportName\>.vb. In code editor, the code for the data method displays in a class that has the same name as the report. The following template is provided for a Visual Basic data method:
    
    ``` vb
    <DataMethod(), PermissionSet(SecurityAction.Assert, Name:="FullTrust")> 
    Public Shared Function GetCustomerData() As System.String
    
    End Function
    ```
    
    In order to use a data method as a source of data for a report dataset, it must return an IEnumerable\<DataRow\> or DataTable instance. When using the data method to return the values for a dataset, dataset parameters are created for each parameter in the data method. Parameters display on the report to allow the end-user to filter data. For more information about parameters for datasets, see [Parameters Overview](parameters-overview.md).

15. In the code for the data method, specify an appropriate return value.

16. Remove the line of code for the exception that states the data method is not implemented, and then add your code to the method. The following code example returns a single row of data at a time using an IEnumerable\<DataRow\> instance. This data method can be used when creating a report data set. The following example shows a data method that creates and returns inventory data for a single row of data at a time. In an actual application, the code in the data method would retrieve the data from some other source and return it one row at a time.
    
    ``` vb
    <DataMethod(), PermissionSet(SecurityAction.Assert, Name:="FullTrust")>
    Public Shared Function GetCustomerData() As DataTable
        'Define a data table.
        Dim table As New System.Data.DataTable()
        table.Columns.Add(New DataColumn("ItemID", Type.[GetType]("System.Int32")))
        table.Columns.Add(New DataColumn("Name", Type.[GetType]("System.String")))
        table.Columns.Add(New DataColumn("Description", Type.[GetType]("System.String")))
        table.Columns.Add(New DataColumn("Cost", Type.[GetType]("System.Decimal")))
        table.Columns.Add(New DataColumn("SellingPrice", Type.[GetType]("System.Decimal")))
    
        Dim row As DataRow = Nothing
        row = table.NewRow()
        row.ItemArray = New Object() {1734, "Clamp", "Workbench Clamp", 12.48, 17.99}
        table.Rows.Add(row)
    
        row = table.NewRow()
        row.ItemArray = New Object() {1983, "Saw", "Wooden Handle Saw", 7.89, 11.99}
        table.Rows.Add(row)
    
        row = table.NewRow()
        row.ItemArray = New Object() {6728, "Screwdriver", "Standard Screwdriver", 2.75, 3.99}
        table.Rows.Add(row)
    
        row = table.NewRow()
        row.ItemArray = New Object() {4920, "Nails", "Roofing Nails 5lbs", 12.45, 15.99}
        table.Rows.Add(row)
    
        row = table.NewRow()
        row.ItemArray = New Object() {4829, "Tape Measure", "25 ft Tape Measure", 12.87, 16.99}
        table.Rows.Add(row)
    
        row = table.NewRow()
        row.ItemArray = New Object() {2893, "Nails", "Finish Nails", 3.9, 5.99}
        table.Rows.Add(row)
    
        Return table   
    End Function
    ```

17. To build the project, in Solution Explorer right-click the solution that contains the business logic project, and then click **Build**. Building the solution ensures that the report model and the code are in sync. The name of the data method, parameters, and all other properties that you defined in the code are now reflected in Model Editor.

The next step is to [bind a dataset to the data method](how-to-bind-a-dataset-to-a-data-method.md) as a source of report data or [invoke the data method by using an expression](how-to-use-a-data-method-in-an-expression.md).

## See also

[Report Data Method Overview](report-data-method-overview.md)

[How to: Define a Data Method in C\#](how-to-define-a-data-method-in-csharp.md)

