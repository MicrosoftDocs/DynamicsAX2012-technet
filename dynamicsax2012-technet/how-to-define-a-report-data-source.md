---
title: 'How to: Define a Report Data Source'
TOCTitle: 'How to: Define a Report Data Source'
ms:assetid: 275748a0-522d-4d6c-839b-4dad8d12a4e5
ms:mtpsurl: https://technet.microsoft.com/library/Cc585332(v=AX.60)
ms:contentKeyID: 28119324
author: tonyafehr
ms.date: 04/17/2013
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.ExternalDataSourceDefinition
---

# How to: Define a Report Data Source 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To retrieve data for your reports, you can use the predefined *Dynamics AX* or *DynamicsAXOLAP* data sources to connect to the Microsoft Dynamics AX application databases. Or, you can define your own data sources. For example, if you want to use a database other than the application database, you must define a data source to specify connection information and a provider type for that database. The following procedure explains how to define a data source.


> [!NOTE]
> <P>When accessing data from the Microsoft Dynamics AX database, it is recommended that you use the predefined Dynamics AX data source to ensure that appropriate security is enforced. When you use the predefined Dynamics AX data source, the data access requests go through the Role and Task security system.</P>



### To define a report data source

1.  In Solution Explorer, right-click the reporting project that you want to add a report data source to, point to **Add**, and then click **Report Data Source**. A data source is added to the project with a name like **ReportDataSource1** and appears in Model Editor.

2.  Select the node for the report data source.

3.  In the **Properties** window, set the following properties:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Connection String</strong></p></td>
    <td><p>The connection string that the report server uses to connect to the data source. The connection string includes a set of name/value pairs to specify connection information, such as server name, database name, and authentication method. Here are some examples.</p>
    <p>SQL</p>
    <p>Server=localhost;Database=LegacyInventoryData;Integrated Security=SSPI</p>
    <p>OLAP</p>
    <p>Data Source=localhost;Initial Catalog=DynamicsAX;Integrated Security=SSPI</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>A name for the data source.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Namespace</strong></p></td>
    <td><p>The namespace for the data source.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Provider</strong></p></td>
    <td><p>The provider for the data source. There are two provider types that you can choose from: SQL and OLAP.</p>
    <div class="alert">

    > [!NOTE]
    > <P>Reports using a SQL provider for the data source are not supported to run in a batch, run on the server, or run from EP.</P>
    > <P>Reports using an OLAP provider for the data source may show an N/A item group if the cube has a dimension that is striped by Company. If you need to exclude N/A values, use MDX to filter the N/A values in the report.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


Next, you can add a dataset and use the data source for a report. For more information, see [How to: Define a Report Dataset](how-to-define-a-report-dataset.md).

## See also

[Report Data Overview](report-data-overview.md)

