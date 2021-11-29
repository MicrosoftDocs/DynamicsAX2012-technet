---
title: About selecting jobs in the Kanban board for transfer jobs by using a bar code reader
TOCTitle: About selecting jobs in the Kanban board for transfer jobs by using a bar code reader
ms:assetid: 683971b9-cff7-402b-a165-5d9612fd06fa
ms:mtpsurl: https://technet.microsoft.com/library/JJ713629(v=AX.60)
ms:contentKeyID: 49643125
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- bar code reader
- scan kanban job
- scan job
- select kanban job
- select job
audience: Application User
ms.search.region: Global
---

# About selecting jobs in the Kanban board for transfer jobs by using a bar code reader 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you use a bar code reader to select a job in the **Kanban board for transfer jobs** form, the display mode of the kanban board changes. Only a single kanban job is displayed. In this mode, the following conditions apply:

  - Only the selected job is displayed. The full results of the jobs filter are not displayed.

  - The details of the selected job are displayed.

  - The **Messages** FastTab displays messages only for the selected job.

  - You can change the status of the job by using the functions that are available on the **Action Pane**. The **Kanban board for transfer jobs** form continues to display only a single job during this time.

  - You can update the information in the list of jobs manually by clicking **Refresh (F5)** on the **View** tab of the **Action Pane**. After you refresh the information, the full results for the job filter are once again displayed.

The status of the selected job, and the status of any pegged jobs for event kanbans, determine whether you can process the job further. The following table displays information about these statuses and tasks:

  - The statuses that are available for jobs, or for the handling units that are referenced by the jobs.

  - Each task that you can perform for the job.

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job type</p></th>
<th><p>Job status or handling unit status</p></th>
<th><p><strong>Update picking list</strong></p></th>
<th><p><strong>Start</strong></p></th>
<th><p><strong>Update registration</strong></p></th>
<th><p><strong>Complete</strong></p></th>
<th><p><strong>Empty</strong></p></th>
<th><p><strong>Create event kanbans</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Transfer</p></td>
<td><ul>
<li><p><strong>Not planned</strong></p></li>
<li><p>No pegged jobs, or pegged jobs are <strong>Completed</strong></p></li>
</ul></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Transfer</p></td>
<td><ul>
<li><p><strong>Not planned</strong></p></li>
<li><p>The pegged job is not <strong>Completed</strong></p></li>
</ul></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Transfer</p></td>
<td><p><strong>In progress</strong></p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Transfer</p></td>
<td><p><strong>Completed</strong></p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Transfer or process</p></td>
<td><p><strong>Empty</strong></p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Transfer or process</p></td>
<td><p>A kanban card is not found</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Transfer or process</p></td>
<td><p>A kanban card is found, but it is not assigned to a kanban</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Process</p></td>
<td><ul>
<li><p><strong>Not planned</strong></p></li>
<li><p><strong>Prepared</strong></p></li>
<li><p><strong>In progress</strong></p></li>
</ul></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Process</p></td>
<td><p><strong>Completed</strong></p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


## See also

[Kanban board for transfer jobs (form)](https://technet.microsoft.com/library/hh781100\(v=ax.60\))

  


