---
title: About courses
TOCTitle: About courses
ms:assetid: df219e6d-ef10-41b7-922e-bcea26dd1554
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551281(v=AX.60)
ms:contentKeyID: 49384140
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About courses [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Courses** list page to maintain information about the courses that you offer to your workers.

## Setup prerequisites

The following information is required information for courses. Before you create courses, you must set up this information.

  - **Course types**

The following information is optional information that you can specify for courses. If you know that you will be entering this information for courses, you should set up this information before you create course records.

  - **Classroom groups**

  - **Course groups**

  - **Course locations**

  - **Classrooms**

  - **Instructors**

## Course types

You can use course types to categorize courses according to the structure or content of the course. You can create course types in the **Course types** form. You must select a course type when you create a course record.

## Course setup type

The following table lists the three setup types for courses. Setup types determine the structure of the course.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Setup type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Standard</strong></p></td>
<td><p>Select this type for courses that will not have a daily agenda. This is the default setup type when you create a new course.</p></td>
</tr>
<tr class="even">
<td><p><strong>Agenda</strong></p></td>
<td><p>Select this type so that you can set up the individual items on the programs for each day for the course.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Agenda + session</strong></p></td>
<td><p>Select this type for the more complex courses. For example, you can divide the agenda for the course into tracks and sessions.</p>
<ul>
<li><p><strong>Track</strong> – Tracks are specific subject areas for a course.</p></li>
<li><p><strong>Sessions</strong> – Sessions divide up tracks and can cover specific processes or techniques that are relevant to each track.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Course tasks

For each course, you can complete the following tasks.

  - Register participants.

  - Specify a registration deadline.

  - Define the minimum and maximum number of participants.

  - Assign a course location and classroom.

  - Recommend hotels to course participants.

  - Create a course description, which you can then advertise on Enterprise Portal.


> [!NOTE]
> <P>You can delete only courses that no participants have registered for.</P>



For more information, see [Key tasks: Courses](key-tasks-courses.md).

## Course statuses

The following table lists the possible course statuses and the actions that you can complete when the course has a specific status.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Status</p></th>
<th><p>Actions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Created</strong></p></td>
<td><ul>
<li><p>Enter and modify course information.</p></li>
<li><p>Change the course status to <strong>Open</strong> so that workers can register for the course.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Open</strong></p></td>
<td><ul>
<li><p>Register participants for the course.</p></li>
<li><p>Remove participants from the course.</p></li>
<li><p>Confirm participants for the course.</p></li>
<li><p>Change the course status to <strong>Closed</strong> or <strong>Canceled</strong>.</p></li>
<li><p>Plan questionnaires for participants whose status is <strong>Confirmed</strong>.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Closed</strong></p></td>
<td><p>You can reopen the course.</p></td>
</tr>
<tr class="even">
<td><p><strong>Canceled</strong></p></td>
<td><p>You can reopen the course.</p></td>
</tr>
</tbody>
</table>


## Course participants

Course participants are employees, applicants, or contact persons who participate in a training course or event. You can only register participants for open courses.

The minimum and maximum number of participants that you can register for a course is defined on the **General** FastTab in the **Courses** form.

## Integration with absence reporting

You can generate absence transactions when a course participant is confirmed in a course if you select the **Integration to absence?** check box in the **Human resources parameters** form. For more information, see [Set up human resources parameters](set-up-human-resources-parameters.md).

## See also

[Key tasks: Courses](key-tasks-courses.md)

[Course types (form)](https://technet.microsoft.com/en-us/library/aa618160\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

