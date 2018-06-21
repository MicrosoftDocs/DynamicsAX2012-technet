---
title: Reserve a specific worker for a project
TOCTitle: Reserve a specific worker for a project
ms:assetid: 5cf0c51f-50fc-466f-91ba-bf7eb695fcd8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn532263(v=AX.60)
ms:contentKeyID: 59930614
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.ProjResourcesListPageBookingDialog
- MsDynAx060.Forms.ProjResourcesListPageBookingDialog
---

# Reserve a specific worker for a project [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to assign specific workers to specific projects in Microsoft Dynamics AX. To find resources for a project, you can view a list of workers in a legal entity who are available to be scheduled for projects. Reserve a worker by creating a hard booking, which commits the worker to the project, or a soft booking, which tentatively assigns the worker to the project.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



**Staffing options in earlier versions of Microsoft Dynamics AX 2012**

The method of reserving workers that is described in this topic is an alternative to the staffing options that were introduced in earlier versions of Microsoft Dynamics AX 2012. Those options include the following:

  - Start with a project schedule and find qualified workers to fill its roles.
    
    For information about finding workers based on project requirements, refer to one of the following topics:
    
      - [Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012](key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012.md)
    
      - [Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 R2](key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012-r2.md)
    
      - [Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7](key-tasks-create-a-schedule-based-on-a-project-in-ax-2012-r3-or-ax-2012-r2-cu7.md)

  - Start with a list of all workers who are both qualified and available and assign them to open project roles.
    
    For information about staffing projects based on which workers are currently available, see [Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md)

### Reserve a worker for a project

1.  Click **Project management and accounting** \> **Common** \> **Project resources** \> **Resources**.

2.  In the **Resources** list, select the worker or workers whom you want to reserve for a project.

3.  On the **Action Pane**, on the **Project resource** tab, in the **Reserve** group, choose the type of reservation you want to make. The following table describes the purpose of each reservation type.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Reservation type</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Hard book</strong></p></td>
    <td><p>Make a firm reservation for the worker in the project. When you select this option, the worker’s time cannot be reserved for other project assignments.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Soft book</strong></p></td>
    <td><p>Make a tentative reservation for the worker in the project. When you select this option, the worker’s time can still be reserved for other projects.</p></td>
    </tr>
    </tbody>
    </table>


4.  In the **Worker** column, select a worker’s name.

5.  In the **Project name** field, select the project that you want to reserve the worker for.

6.  Depending on the reservation type that you selected in step 3, click **Hard booking** or **Soft booking**.

## See also

[Identify and assign qualified workers to projects](identify-and-assign-qualified-workers-to-projects.md)

[About resource management for projects](about-resource-management-for-projects.md)

[View booking details (form)](https://technet.microsoft.com/en-us/library/dn532267\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

