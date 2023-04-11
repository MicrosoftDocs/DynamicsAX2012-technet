---
title: 'How to: Bind a Dataset to a Data Method'
TOCTitle: 'How to: Bind a Dataset to a Data Method'
ms:assetid: 8c5f0eb2-4329-40de-90a5-6861bb3c2551
ms:mtpsurl: https://technet.microsoft.com/library/Hh538450(v=AX.60)
ms:contentKeyID: 39508874
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Bind a Dataset to a Data Method 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can access non-Microsoft Dynamics AX data in a data method and use the data in a Microsoft Dynamics AX report. This topic describes how to bind a dataset to a data method when you want to display non-Microsoft Dynamics AX data on a report. For information about how to define a data method, see [How to: Define a Data Method in C\#](how-to-define-a-data-method-in-csharp.md). When the reporting framework recognizes the data method as a data source, you can see the data method in the **Select a Data Method** dialog box. To be recognized, the following conditions must be true:

  - The return value of the data method must be an IEnumerable\<DataRow\> instance.

  - The class and report must have the same name. This means that a data method is specific to one report.

  - You must build the business logic project.

  - You must add the business logic project to the AOT.

If you want to display Microsoft Dynamics AX data on your report, you should use a report data provider or a query data source. For more information, see [Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md).


> [!TIP]
> <P>You will not find examples of reports that use a dataset bound to a data method included with Microsoft Dynamics AX.</P>



### To bind a dataset to a data method

1.  In Visual Studio, from the **File** menu, point to **New** and then click **Project**.

2.  In the **New Project** window, click the **Microsoft Dynamics AX** installed template and then click the **Report Model** template.

3.  Give the reporting project a name and then click **OK**.

4.  In Solution Explorer, right-click the reporting project, point to **New**, and then click **Report**.

5.  In Model Editor, select the report. In the Properties window, the **Data Method Library** property must be set to the business logic project that contains the data method that you will bind the dataset to. If the report is in the same solution as the business logic project, the reporting framework will default a business logic project. You can also set the **Data Method Library** property to point to a business logic project in a different solution.

6.  In Model Editor, right-click the **Datasets** node and then click **Add Dataset**.

7.  In the Properties window, set the **Data Source Type** property to **Business Logic**.

8.  Click the **Query** property ellipsis **(…)** button.

9.  In the **Select a Data Method** window, select a data method from the list and then click **OK**. This window displays a list of all data methods that are available for the report.
    
    You can also execute data methods to view the results in the results pane. To execute a data method, select the data method in the list, and then click the execute query button located at the top of the window. Alternatively, you can press F5 to execute a data method.
    
    If a data method has parameters, a dialog box displays that lets you specify parameter values. If a parameter is a collection, it can contain a single value or a set of values. For a single value, simply supply the value. For a set of values, specify a semicolon-separated list (such as element1; element2; element3).

In Model Editor, expand the **Fields** node. The report model lists the fields that are defined in the data method. Next you can create a report design to use the data in a report. For more information, see [How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md).

## See also

[Report Data Method Overview](report-data-method-overview.md)

[How to: Define a Data Method in C\#](how-to-define-a-data-method-in-csharp.md)

