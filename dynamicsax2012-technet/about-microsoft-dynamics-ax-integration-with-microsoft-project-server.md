---
title: About Microsoft Dynamics AX integration with Microsoft Project Server
TOCTitle: About Microsoft Dynamics AX integration with Microsoft Project Server
ms:assetid: 788d2018-27f7-4962-9615-4a3e522b5e1e
ms:mtpsurl: https://technet.microsoft.com/library/Gg213008(v=AX.60)
ms:contentKeyID: 36058225
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- integrate
- office project
- project server
audience: Application User
ms.search.region: Global
---

# About Microsoft Dynamics AX integration with Microsoft Project Server 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To help your project management organization gain better visibility into its projects and project resources, and to manage them more effectively, you can combine the Project management and accounting capabilities of Microsoft Dynamics AX with those of Microsoft Project Server.

You can use the flexible task hierarchy in Project Server to create a hierarchical structure that resembles the hierarchical structure of a project in Microsoft Dynamics AX. Corresponding hierarchies make it possible for information about projects, subprojects, and activities to flow between the two programs.


> [!NOTE]
> <P>In Project Server, data that is specific to Microsoft Dynamics AX is presented as custom fields. These fields are indicated by the prefix “DAX_.” For example, company information is reported in the <STRONG>DAX_03_Company</STRONG> field.</P>




> [!NOTE]
> <P>Beginning in cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can also integrate projects in Microsoft Dynamics AX with the desktop version of Microsoft Project and with SharePoint Online. For more information, see <A href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</A>.</P>



## Synchronizing data

After you integrate the two programs and set up synchronization between them, data changes in one program are updated in the other. As a result, your project records are current in both programs.

As part of the synchronization process, actual costs for labor, expenses, and revenue that are posted in Microsoft Dynamics AX are updated in Project Server. Any changes to project or task information in Project Server are updated in the Microsoft Dynamics AX database.

After synchronization you can, for example, view both budgeted and actual costs for hour and expense transactions and the revenue of these projects in Project Server. Then you can integrate the project work for billing and revenue back into projects that are maintained in Microsoft Dynamics AX.

You can also use the complex resource scheduling capabilities of Project Server for a project that you are managing in Microsoft Dynamics AX. Actual costs for worker hours and expenses that are posted in both the Microsoft Dynamics AX client and Enterprise Portal for Microsoft Dynamics AX can then be shared with Project Server.

## Viewing the synchronization status

You can view both the synchronization status of an entity and the transactions that are associated with the entity. When you synchronize entities between Microsoft Dynamics AX and Project Server, you can use the log to view and manage all entity transactions that are synchronizing back and forth between the programs.

  - Click **System administration** \> **Inquiries** \> **Microsoft Project Server integration** \> **Integration log**.

## Understanding terminology

The focus of the integration between Microsoft Dynamics AX and Project Server is on projects, activities, and workers. However, some terminology that is used in Project Server differs from terminology than is used in Microsoft Dynamics AX. The following table shows the terms that are used in Microsoft Dynamics AX and the corresponding terms in Project Server.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Microsoft Dynamics AX</p></th>
<th><p>Project Server</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Project</p></td>
<td><p>Project</p></td>
</tr>
<tr class="even">
<td><p>Activities</p></td>
<td><p>Tasks</p></td>
</tr>
<tr class="odd">
<td><p>Workers</p></td>
<td><p>Resources</p></td>
</tr>
</tbody>
</table>


## Finding detailed setup information

For detailed information about how to integrate Microsoft Dynamics AX and Project Server so that you can use the features of both programs to manager your projects, see the white paper [Microsoft Project Server 2010 Integration with Microsoft Dynamics AX 2012](https://go.microsoft.com/fwlink/?linkid=215155).

## See also

[Configuring Microsoft Project Server integration](configuring-microsoft-project-server-integration.md)

[Microsoft Project Server integration global settings (form)](https://technet.microsoft.com/library/hh209389\(v=ax.60\))

[Microsoft Project Server integration settings (form)](https://technet.microsoft.com/library/hh242729\(v=ax.60\))

[Integrate a worker in Microsoft Dynamics AX with Microsoft Project Server](integrate-a-worker-in-microsoft-dynamics-ax-with-microsoft-project-server.md)

  


