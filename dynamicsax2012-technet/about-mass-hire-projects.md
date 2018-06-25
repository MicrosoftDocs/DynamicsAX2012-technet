---
title: About mass hire projects
TOCTitle: About mass hire projects
ms:assetid: 15d6e996-fdb1-405d-abbd-72bca67e6dc3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569885(v=AX.60)
ms:contentKeyID: 36676370
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About mass hire projects [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use mass hire projects when you hire multiple workers at one time, such as when you hire to meet a seasonal demand. Creating a mass hire project is useful because you can create position records, worker records, and worker assignments for positions at the same time. When you create positions for a mass hire project, you can specify the following information:

  - The number of positions to create

  - The worker type of the people that you will hire for the positions

  - The department and the job that are associated with the positions

  - The full-time equivalent value of the position

For instructions on how to create and use a mass hire project, see [Key tasks: Mass hire projects](key-tasks-mass-hire-projects.md).

**Example**

In the summer, you usually hire 15-20 part-time college students to fill available internships in your company. This year, you want to hire five accountants, five order processors, and five cashiers. Instead of creating each position record and worker record separately, you create one mass hire project called “SummerInterns”. The project start and end dates correlate to the start and end dates of the position durations for the positions you create for the mass hire project.

In the **Mass hire projects** form, select the “SummerInterns” project and then click **Open project**. Now that the mass hire project is open, click **Create positions** and enter information about the accountant position. You can indicate that you want five accountant positions to be created that use the same information, and then click **OK**. Repeat this process for the order processor and cashier positions.

After finding students to hire for the positions, you enter each student’s information in the position details for the position that you will hire them for. When you have entered all of the position details, select the position in the **Mass hire projects** form, and then click **Hire**. A position record will be created for each position and a worker record will be created and assigned to the correct position for each person who you hire.

## Mass-hire project statuses

A mass hire project can have the following statuses.

  - **Created**

  - **Open**

  - **Closed**

In the **Mass hire project** form, click **Open project** or **Close project** to change the status of a mass hire project. The following table describes what you can do with a project according to its status.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Status</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Created</strong></p></td>
<td><p>You can create and modify information, but cannot create positions for the project. This is the default status for new projects.</p></td>
</tr>
<tr class="even">
<td><p><strong>Open</strong></p></td>
<td><p>You can modify the project details, create positions for the mass hire project, and hire people for the positions. This is the status for active projects.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Closed</strong></p></td>
<td><p>You cannot add positions to the project. To add positions to the mass hire project, open the project again. This is the status for completed projects.</p>
<div class="alert">

> [!NOTE]
> <P>Before you can close a mass hire project, all positions in the project must have either the <STRONG>Created</STRONG> or <STRONG>Closed</STRONG> status.</P>


</div></td>
</tr>
</tbody>
</table>


## See also

[Key tasks: Mass hire projects](key-tasks-mass-hire-projects.md)

[Mass hire projects (form)](https://technet.microsoft.com/en-us/library/aa591824\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

