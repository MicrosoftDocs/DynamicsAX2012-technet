---
title: Set up Human resources workflows
TOCTitle: Set up Human resources workflows
ms:assetid: 177a7979-752a-4ff6-b0ef-9a1ea5324e1d
ms:mtpsurl: https://technet.microsoft.com/library/Dn876703(v=AX.60)
ms:contentKeyID: 63385346
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up Human resources workflows 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

## The types of workflows you can create

The following table lists the types of workflows that you can create in Human resources.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Use this type to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Worker actions hire</strong></p></td>
<td><p>Create approval workflows for hiring workers.</p>
<p>This option is available only if Microsoft Dynamics AX 2012 R3 or later is installed and the <strong>Personnel actions</strong> configuration key (HcmPersonnelActions) is selected.</p></td>
</tr>
<tr class="even">
<td><p><strong>Worker actions terminate</strong></p></td>
<td><p>Create approval workflows for employment termination.</p>
<p>This option is available only if AX 2012 R3 or later is installed and the <strong>Personnel actions</strong> configuration key (HcmPersonnelActions) is selected.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Worker actions transfer</strong></p></td>
<td><p>Create approval workflows for worker transfers.</p>
<p>This option is available only if AX 2012 R3 or later is installed and the <strong>Personnel actions</strong> configuration key (HcmPersonnelActions) is selected.</p></td>
</tr>
<tr class="even">
<td><p><strong>Human resources actions workflow</strong></p></td>
<td><p>Create approval workflows for position actions. For example, use a workflow when you create new positions or modify existing positions.</p>
<p>This option is available only if Microsoft Dynamics AX 2012 R2 or later is installed and the <strong>Personnel actions</strong> configuration key (HcmPersonnelActions) is selected.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Time and attendance days total workflow</strong></p></td>
<td><p>Create approval workflows for attendance days total records.</p></td>
</tr>
<tr class="even">
<td><p><strong>Time and attendance journal registration workflow</strong></p></td>
<td><p>Create approval workflows for journal registration records.</p></td>
</tr>
</tbody>
</table>


## See also

[Journal names (form) (Project)](https://technet.microsoft.com/library/aa617509\(v=ax.60\))

[Journal names setup (form)](https://technet.microsoft.com/library/aa552517\(v=ax.60\))

[Configure personnel actions](configure-personnel-actions.md)

  


