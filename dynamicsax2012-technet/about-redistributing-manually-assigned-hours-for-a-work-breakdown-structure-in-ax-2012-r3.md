---
title: About redistributing manually assigned hours for a work breakdown structure in AX 2012 R3
TOCTitle: About redistributing manually assigned hours for a work breakdown structure in AX 2012 R3
ms:assetid: 0b7cf6a6-d893-43ef-9481-7805848f3379
ms:mtpsurl: https://technet.microsoft.com/library/Dn783114(v=AX.60)
ms:contentKeyID: 62830461
ms.date: 08/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About redistributing manually assigned hours for a work breakdown structure in AX 2012 R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how hours are redistributed among workers who were manually assigned to WBS tasks when workers are removed from their task assignments.

When you manually assign workers to tasks in a WBS, you can assign workers who have already been added to the project team and whose time has already been booked for the project. You can also search for other available workers and assign them to the task.

With either method, you can divide task hours evenly among multiple workers. When you assign hours to workers who were not already part of the project team, you can also choose to assign a different number of hours to each worker.


> [!NOTE]
> <P>For information about how to assign workers to tasks manually in a WBS using either method, see <A href="assign-workers-to-tasks-manually-in-a-work-breakdown-structure-in-ax-2012-r3.md">Assign workers to tasks manually in a work breakdown structure in AX 2012 R3</A>.</P>



No matter which method you use, if you remove one or more workers from tasks in the WBS after making assignments, the total number of hours is redistributed evenly among all workers. This is the case even if you had manually assigned different numbers of hours to start with.

## Example 1: Redistributing hours that were already evenly distributed

A project task requires 60 hours of work, and you divide those hours evenly among six workers, so that each worker is assigned 10 hours of work.

You then remove two workers from the task. The total number of task hours is then redistributed evenly among the remaining workers, with each of the four being assigned 15 hours, as illustrated in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Worker</p></th>
<th><p>Sixty hours distributed evenly among six workers</p></th>
<th><p>Sixty hours redistributed evenly among four workers</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Worker 1</p></td>
<td><p>10</p></td>
<td><p>15</p></td>
</tr>
<tr class="even">
<td><p>Worker 2</p></td>
<td><p>10</p></td>
<td><p>15</p></td>
</tr>
<tr class="odd">
<td><p>Worker 3</p></td>
<td><p>10</p></td>
<td><p>15</p></td>
</tr>
<tr class="even">
<td><p>Worker 4</p></td>
<td><p>10</p></td>
<td><p>15</p></td>
</tr>
<tr class="odd">
<td><p>Worker 5</p></td>
<td><p>10</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>Worker 6</p></td>
<td><p>10</p></td>
<td><p>0</p></td>
</tr>
</tbody>
</table>


## Example 2: Redistributing hours that were not evenly distributed

When you manually assign workers to a task who were not already part of the project team, you can choose to assign each one a specific number of task hours.

A task requires 60 hours of work, and you assign 20 hours to Worker 1, 15 hours to Worker 2, 10 hours to Worker 3, and five hours each to the remaining three workers.

You then remove two of the workers who are assigned five hours each from the task. The total number of task hours is then redistributed evenly among the remaining workers, instead of only the extra ten hours, as illustrated in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Worker</p></th>
<th><p>Sixty hours distributed unevenly among six workers</p></th>
<th><p>Sixty hours redistributed evenly among four workers</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Worker 1</p></td>
<td><p>20</p></td>
<td><p>15</p></td>
</tr>
<tr class="even">
<td><p>Worker 2</p></td>
<td><p>15</p></td>
<td><p>15</p></td>
</tr>
<tr class="odd">
<td><p>Worker 3</p></td>
<td><p>10</p></td>
<td><p>15</p></td>
</tr>
<tr class="even">
<td><p>Worker 4</p></td>
<td><p>5</p></td>
<td><p>15</p></td>
</tr>
<tr class="odd">
<td><p>Worker 5</p></td>
<td><p>5</p></td>
<td><p>0</p></td>
</tr>
<tr class="even">
<td><p>Worker 6</p></td>
<td><p>5</p></td>
<td><p>0</p></td>
</tr>
</tbody>
</table>


Any time you remove workers from a WBS task assignment, it is a good practice to review the resulting distribution of hours and make any scheduling adjustments that you might require.

## See also

[Assign workers to tasks manually in a work breakdown structure in AX 2012 R3](assign-workers-to-tasks-manually-in-a-work-breakdown-structure-in-ax-2012-r3.md)

[About work breakdown structures](about-work-breakdown-structures.md)

[Create a work breakdown structure of tasks for a project](create-a-work-breakdown-structure-of-tasks-for-a-project.md)

[Work breakdown structure (form)](https://technet.microsoft.com/library/hh209089\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

  


