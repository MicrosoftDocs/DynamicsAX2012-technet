---
title: Report Data Method Overview
TOCTitle: Report Data Method Overview
ms:assetid: 39b24dd9-f078-4197-8468-fb7c193eaeec
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc587341(v=AX.60)
ms:contentKeyID: 28119344
ms.date: 05/28/2013
mtps_version: v=AX.60
---

# Report Data Method Overview [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can retrieve and manipulate the data that displays in your reports by providing logic in a data method using C\# or Visual Basic. However, you should use a report data provider (RDP) class or query data source when possible because the framework provides greater support. When using an RDP class or query data source, the framework has optimized performance and makes use of Microsoft Dynamics AX metadata.

When you define a report in Model Editor, the reporting framework handles format and drill through links for you. If you need something other than the framework defaults, you can use a data method.

The following list describes common scenarios where you should use this approach:

  - Format data or define a color mapping based on logic.

  - Connect to a data source other than Microsoft Dynamics AX using Web services or any service that exposes an Open Data Protocol (OData) feed.
    

    > [!NOTE]
    > <P>If the database that contains other than Microsoft Dynamics AX data is SQL or OLAP, you must define a custom data source using Windows PowerShell cmdlets. For more information, see <A href="administering-microsoft-dynamics-ax-by-using-windows-powershell.md">Administering Microsoft Dynamics AX by using Windows PowerShell</A>.</P>



  - Define the URL target for a drill through navigation link on a report.

For more information about other data sources, see [Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md). This topic provides a description of the key concepts involved in defining data methods for reports.

## Structure of Data Methods

A data method is a method that contains the \[DataMethod()\] attribute. Only methods with this attribute are recognized as data methods by the reporting tools. You must build the business logic project that contains your data methods before you can use the data methods in your report.

The following code contains a data method called GetDefaultColorDark. The data method defines a parameter in the signature called index. The ColorHelper class provides additional color options. This is a common example used in Microsoft Dynamics AX reports to control the color schemes applied to charts. To see this example, in the Application Explorer, open **Visual Studio Projects** \> **C Sharp Projects**, right-click **CaseReports.BusinessLogic**, and then click **Edit**. To see the report definition that uses the data method in an expression, open **Visual Studio Projects** \> **Dynamics AX Model Projects**, right-click **CaseReports**, and then click **Edit**. The data method defines a parameter in the signature called index. The ColorHelper class provides additional color options. This is a common example used in Microsoft Dynamics AX reports to control the color schemes applied to charts.

    public partial class Case_MyCases
    [DataMethod(), PermissionSet(SecurityAction.Assert, Name = "FullTrust")]
    public static string GetDefaultColorDark(int index)
    {
        return ColorHelper.GetDefaultColorDark(index);
    }

For more information about how to use a data method in an expression, see [How to: Use a Data Method in an Expression](how-to-use-a-data-method-in-an-expression.md).

## Business Logic Projects for Data Methods

When you create a data method within Model Editor, a business logic project is added to the solution and a template for the data method is placed in a code file in the business logic project. To view the code for a data method, right-click the data method in Model Editor, and then click **View Code**, or double-click the code file in Solution Explorer.

When you build a report solution with a business logic project, the report model is synced with the code. You must build the solution to see added parameters in code reflected in the report model. During deployment, business logic assemblies are built and deployed to the report server. For more information about the deployment process, see [Report Integration and Customization Overview](report-integration-and-customization-overview.md).

## Modifying and Deleting Data Methods

To modify or delete a data method, you must modify or delete the data method in Model Editor and in the code. When you modify or delete a data method in Model Editor, the code is unchanged for the data method in the code file.

You must be especially careful when modifying data methods. Data methods can be referenced from datasets and expressions throughout a report. If you make a breaking change to a data method in the code, you must manually update all references to the data method wherever it is used in the report. The following actions can result in a breaking change and cause errors in your report:

  - Deleting a data method

  - Removing the \[DataMethod()\] attribute from the data method

  - Changing the name of a data method

  - Changing the return value of a data method

  - Adding or removing parameters in a data method

  - Changing the type of a parameter in a data method

Model validation is in place to help identify broken references and invalid expressions. When you build a project, error messages for broken references and invalid expressions display in the **Error List** window.

## Data Methods in C\# or Visual Basic

You can provide code for a data method by using C\# or Visual Basic. The default template that is used for a data method is provided in C\#. When you add a data method in Model Editor a C\# project is added to the solution. The project will contain a .cs class that has the same name as the report and the template for a data method.

To code the data method in Visual Basic, select the report in Model Editor and in the Properties window, use the drop-down to set the **Data Method Library** property to a Visual Basic project. The drop-down lists the projects that have been added to the AOT. Then you can add a data method in Model Editor and a .vb class that has the same name as the report will be added to the Visual Basic project. For more information, see [How to: Define a Data Method in Visual Basic](how-to-define-a-data-method-in-visual-basic.md).


> [!NOTE]
> <P>Before you build a Visual Basic project, you must clear out the namespace setting of the Visual Basic project. In Solution Explorer, right-click the project, and then click <STRONG>Properties</STRONG>. In the <STRONG>Application</STRONG> area, delete the text in the <STRONG>Root namespace</STRONG> field.</P>



## Data Methods for a Non-Microsoft Dynamics AX Data Source

You can define access to non-Microsoft Dynamics AX data in a data method. To do this, add a dataset to a report, then set the **Data Source Type** property to **Business Logic**. In the Properties window, for the **Query** property, click the **(…)** ellipsis button to open the **Select a Data Method** dialog box that contains the list of recognized data methods. For a data method to be recognized, the following conditions must be true:

  - The return value must be an IEnumerable\<DataRow\> instance.

  - The class and report must have the same name. This means that you can only use a data method for one report.

  - You must build the project.

  - You must add the project to the AOT.

You will not find examples of reports that use a dataset bound to a data method included with Microsoft Dynamics AX.

## Data Methods for Custom Drill Throughs

A drill through on a report is a link on a report to additional data. The target of the drill through is determined by the reporting framework using metadata. If you want a different target for the drill through, you can create a custom drill through and use a data method to generate a URL to a specific Microsoft Dynamics AX form or provide logic for the drill through. For more information, see [Adding Links to a Report](adding-links-to-a-report.md).

You can find examples of this scenario in Application Explorer by going to **Visual Studio Projects** \> **C Sharp Projects** and then find a report name to view the data methods for. The name of the project must start with the name of the report. For example, the data methods for the AssetAddition report are defined in the **AssetAdditionReport.BusinessLogic** project. To see the report definition, in the Application Explorer, open **Visual Studio Projects** \> **Dynamics AX Model Projects**, right-click **AssetAdditionReport** and then click **Edit**. To see the report in Microsoft Dynamics AX, open **Fixed assets** \> **Reports** \> **Fixed asset addition**.

## Data Methods in Report Expressions

There are many areas where you can add expressions to your reports. For example, you can create an expression for a field to perform a calculation or change the data that displays for the field. You can use a data method in an expression. In this case, the expression references the data method in the business logic project. Expression Editor displays a list of data methods that are available to the report. For information about how to use Expression Editor, see [Edit Expression Overview](edit-expression-overview.md). For information about how to create expressions, see [Expression Examples in Reporting Services](http://go.microsoft.com/fwlink/?linkid=106936).

When you write business logic in a data method, you will call the data method from an expression. You can access X++ code that is defined in Microsoft Dynamics AX using the managed programming interface for reports that is defined in the [Reports](https://technet.microsoft.com/en-us/library/cc601396\(v=ax.60\)) namespace. A data method can be used in multiple expressions in a report, so that the business logic that you define is reusable.

## See also

[How to: Define a Data Method in C\#](how-to-define-a-data-method-in-csharp.md)

[How to: Define a Report Dataset](how-to-define-a-report-dataset.md)

[Reports](https://technet.microsoft.com/en-us/library/cc601396\(v=ax.60\))

