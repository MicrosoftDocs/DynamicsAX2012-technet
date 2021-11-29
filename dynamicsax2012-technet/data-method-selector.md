---
title: Data Method Selector
TOCTitle: Data Method Selector
ms:assetid: af6beff2-0b44-4bd6-a9b2-0dea8ae29162
ms:mtpsurl: https://technet.microsoft.com/library/Cc573435(v=AX.60)
ms:contentKeyID: 28119565
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- DynamicsDataMethodSelectorHelp
---

# Data Method Selector 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you use business logic to define a dataset for a report, you must specify a data method that is a source of data for the dataset. Only data methods that return a System.Data.IEnumerable instance can be used. When defining the dataset, you can type the data method name for the dataset **Query** property in the **Properties** window. Or, you can click the ellipsis button (…) for the **Query** property to display the **Select a Data Method** window. This window displays a list of all data methods that are available for the report. You can select a data method from the list. You can also execute data methods to view the results in the results pane. The following illustration shows the **Select a Data Method** window.

![Data Method Selector](images/Cc573435.VSReportsDataMethodSelector(AX.60).gif "Data Method Selector")

To execute a data method, select the data method in the list, and then click the execute query button located at the top of the window. Alternatively, you can press F5 to execute a data method. If a data method has parameters, a dialog box displays allowing you to specify parameter values. If a parameter is a collection, specify a single value if the collection has one element or specify a semicolon separated list (such as element1;element2;element3) if the collection contains more than one element. After executing a data method, you can use the buttons located below the results pane to iterate through the results. To select a data method for the dataset, select the data method in the list, and then click **OK**.

## See also

[Report Data Overview](report-data-overview.md)

