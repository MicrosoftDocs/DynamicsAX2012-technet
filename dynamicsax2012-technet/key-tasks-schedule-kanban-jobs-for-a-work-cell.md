---
title: 'Key tasks: Schedule kanban jobs for a work cell'
TOCTitle: 'Key tasks: Schedule kanban jobs for a work cell'
ms:assetid: 465ea32f-4041-4ebb-8963-ba0b505e2e61
ms:mtpsurl: https://technet.microsoft.com/library/Hh802996(v=AX.60)
ms:contentKeyID: 44080971
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- kanban jobs, schedule
- kanban schedule board
- plan a work cell
- plan jobs
- plan kanban jobs
- schedule a work cell
- schedule jobs
- schedule kanban jobs
audience: Application User
ms.search.region: Global
---

# Key tasks: Schedule kanban jobs for a work cell 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Kanban schedule board** form to manually schedule kanban jobs for a work cell. You can complete the following scheduling tasks for one or more selected jobs:

  - Plan jobs in a specific planning period.

  - Plan jobs based on their due dates.

  - Change the sequence of jobs in a planning period.

  - Move jobs to a different planning period.

  - Remove jobs from a planning period.

The **Kanban schedule board** form is interactive, and you can modify information by using the following methods:

  - Drag one or more jobs between areas in the schedule.

  - Select one or more jobs, and then use the relevant functions on the **Action Pane**.

  - Use the keyboard to schedule jobs. For more information, see the “Use the keyboard to schedule jobs” section later in this topic.

When you schedule jobs, the information in the **Kanban schedule board** form is updated as follows:

  - The jobs appear in the correct area of the board.

  - The scheduled capacity for the planning period is updated.

  - The status of the jobs is updated in both the planning section and the **Kanban quantity overview** section.

  - The planning urgency of the kanban rules is recalculated, and the **Kanban quantity overview** section is updated. The most urgent rule is displayed first.

## What do you want to do?

Plan jobs in a specific planning period

Plan jobs based on their due dates

Change the sequence of jobs in a planning period

Move jobs to a different planning period

Remove jobs from a planning period

Use the keyboard to schedule jobs

Find form help

## Plan jobs in a specific planning period

You can schedule jobs that have a **Not planned** status, and you can specify which planning period to schedule the jobs in.

1.  Click the **Unplanned** tab to filter the jobs that are not yet planned for the work cell. Then select one or more jobs.

2.  Drag the jobs to a specific planning period. You can move the jobs to the start or end of a period, or between jobs that are currently scheduled for the period.
    
    The status of the jobs changes from **Not planned** to **Planned**.

Back to top

## Plan jobs based on their due dates

You can schedule jobs that have a **Not planned** status. The jobs are scheduled based on their due dates.

1.  Click the **Unplanned** tab to filter the jobs that are not yet planned for the work cell. Then select one or more jobs.

2.  On the **Action Pane**, on the **Plan** tab, in the **Kanban quantity overview** group, click **Plan**. The jobs are scheduled for the earliest available planning period, based on the due dates of the jobs.
    
    The status of the jobs changes from **Not planned** to **Planned**.
    

    > [!NOTE]
    > <P>The jobs may be scheduled in a future period that you cannot see in the current view of the <STRONG>Kanban schedule board</STRONG> form. You can change the view so that the future period is displayed.</P>



Back to top

## Change the sequence of jobs in a planning period

You can change the sequence of the jobs that are planned for a specific planning period. When you change the sequence of jobs, the status of the jobs does not change. The status remains **Planned**.

1.  In a planning period, select one or more jobs.

2.  Drag the jobs to a different position in the planning period.
    
    –or–
    
    On the **Action Pane**, on the **Plan** tab, in the **Move** group, click **Backward** to move the job one position back in the schedule. Alternatively, click **Forward** to move the job one position ahead in the schedule.

Back to top

## Move jobs to a different planning period

You can reschedule jobs by moving them from one planning period to a different planning period. When you reschedule jobs in a different planning period, the status of the jobs does not change. The status remains **Planned**.

1.  In a planning period, select one or more jobs.

2.  Drag the jobs to a different planning period.
    
    –or–
    
    On the **Action Pane**, on the **Plan** tab, in the **Move** group, follow one of these steps:
    
      - Click **Previous period** to move the jobs to the previous planning period. Then click **Start** to move the jobs to the start of the planning period, or click **End** to move the jobs to the end of the planning period.
    
      - Click **Next period** to move the jobs to the next planning period. Then click **Start** to move the jobs to the start of the planning period, or click **End** to move the jobs to the end of the planning period.

Back to top

## Remove jobs from a planning period

Use one of the following procedures to remove jobs from a planning period.

### Drag a job

1.  In a planning period, select one or more jobs.

2.  Drag the jobs to the **Kanban quantity overview** section.
    
    The status of the jobs changes from **Planned** to **Not planned**.

### Revert the status of a job in a planning period

1.  In a planning period, select one or more jobs.

2.  On the **Action Pane**, on the **Plan** tab, in the **Production** group, click **Revert job status**. Then use the **Revert kanban job status** form to change the status of the jobs to **Not planned**.

### Revert the status of a job in the Kanban quantity overview section

1.  In the **Kanban quantity overview** section, select one or more jobs.

2.  On the **Action Pane**, on the **Plan** tab, in the **Kanban quantity overview** group, click **Revert job status**. Then use the **Revert kanban job status** form to change the status of the jobs to **Not planned**.

Back to top

## Use the keyboard to schedule jobs

You can use the keyboard to schedule jobs in the **Kanban schedule board** form. For more information, see [Shortcut keys](shortcut-keys.md). The following table lists the shortcut keys that you can use.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Shortcut key</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Move forward between areas on the kanban board.</p></td>
<td><p>TAB</p></td>
</tr>
<tr class="even">
<td><p>Move backward between areas on the kanban board.</p></td>
<td><p>SHIFT+TAB</p></td>
</tr>
<tr class="odd">
<td><p>Select a job.</p></td>
<td><p>SPACE</p></td>
</tr>
<tr class="even">
<td><p>Select multiple jobs, one job at a time.</p></td>
<td><p>CTRL+SPACE</p></td>
</tr>
<tr class="odd">
<td><p>Select a range of jobs, starting from the first job that you select.</p></td>
<td><p>SHIFT+SPACE</p></td>
</tr>
<tr class="even">
<td><p>Move selected jobs to the left.</p></td>
<td><p>ALT+LEFT ARROW</p></td>
</tr>
<tr class="odd">
<td><p>Move selected jobs to the right.</p></td>
<td><p>ALT+RIGHT ARROW</p></td>
</tr>
<tr class="even">
<td><p>Complete actions on the <strong>Action Pane</strong>.</p></td>
<td><p>F keys</p></td>
</tr>
<tr class="odd">
<td><p>Move selected jobs to the start of the previous planning period.</p></td>
<td><p>ALT+PAGE UP</p></td>
</tr>
<tr class="even">
<td><p>Move selected jobs to the start of the next planning period.</p></td>
<td><p>ALT+PAGE DOWN</p></td>
</tr>
<tr class="odd">
<td><p>Move selected jobs to the end of the previous planning period.</p></td>
<td><p>CTRL+PAGE UP</p></td>
</tr>
<tr class="even">
<td><p>Move selected jobs to the end of the next planning period.</p></td>
<td><p>CTRL+PAGE DOWN</p></td>
</tr>
</tbody>
</table>


Back to top

## Find form help

[Kanban schedule board (form)](https://technet.microsoft.com/library/hh597153\(v=ax.60\))

[Revert kanban job status (form)](https://technet.microsoft.com/library/hh692491\(v=ax.60\))

  


