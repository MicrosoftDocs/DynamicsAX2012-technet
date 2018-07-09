---
title: 'How to: Find the Data Source For a Report'
TOCTitle: 'How to: Find the Data Source For a Report'
ms:assetid: aab91ecb-c126-4973-bfc3-cb505369406b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg724092(v=AX.60)
ms:contentKeyID: 35133450
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Find the Data Source For a Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

 This topic describes how to find the report data source information from the Application Object Tree (AOT). A report data source can be one of the following:

  - query

  - business logic

  - report data provider

  - AX enum provider

You can also find a report that uses a specific data source as opposed to finding the data source that a report uses. For example, you may want to know which reports use a specific data source.


> [!NOTE]
> <P>You must generate cross-reference information for your application before you can find the data source for a report. The data source will not display if the cross-reference system does not exist or is out of date.</P>



For more information, see [How to: Create the Cross-Reference System](https://technet.microsoft.com/en-us/library/aa877386\(v=ax.60\)).

For information on the data source of a report, see [How to: Define a Report Dataset](how-to-define-a-report-dataset.md).

### To find the data source

  - In the AOT, expand the **SSRS Reports** node, expand the **Reports** node, right-click the report for which you want to find the data source, click **Add-ins**, click **Cross-reference**, and then click **Using (instant view)**. The data source for the report will display in the **Complete cross-reference for the selected nodes** form.

### To determine the report that is using a data source

  - In the AOT, right-click the data source. For example, in the **Data Dictionary** \> **Tables** node, right-click the **CustTable** table, click **Add-ins**, click **Cross-reference**, and then click **Used By**. The reports that use the **CustTable** table as a data source display.

## See also

[Reporting in Microsoft Dynamics AX](reporting-in-microsoft-dynamics-ax.md)

[How to: Create the Cross-Reference System](https://technet.microsoft.com/en-us/library/aa877386\(v=ax.60\))

[How to: Define a Report Dataset](how-to-define-a-report-dataset.md)

[Report Data Overview](report-data-overview.md)

