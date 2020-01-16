---
title: 'Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7'
TOCTitle: 'Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7'
ms:assetid: e55b39f0-f7ed-423b-beb2-0694660f556b
ms:mtpsurl: https://technet.microsoft.com/library/Dn529054(v=AX.60)
ms:contentKeyID: 59643366
author: Khairunj
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project schedule
- project activities
- Menu_Items.Display.ProjResourceAvailability
- Menu_Items.Display.ProjResources
- project tasks
- project worker
audience: Application User
ms.search.region: Global
---

# Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to staff a project based on scheduling and other requirements for the project. By using project-based resource scheduling, you can form a project team by booking workers for project roles that you set up for a project. You can also specify the qualifications that workers must have to fill project roles, book the workers on the team, and then assign workers to specific activities.

The information in this topic applies to Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2 only. For information about project-based scheduling in earlier versions of Microsoft Dynamics AX 2012, see the following topics:

  - For AX 2012 R2: [Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 R2](key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012-r2.md)

  - For AX 2012 or AX 2012 Feature Pack: [Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012](key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012.md)


> [!NOTE]
> <P>In AX 2012 R3 and CU7 and later for AX 2012 R2, you can also staff a project by searching for specific workers first and then assigning them to the project. For more information, see <A href="reserve-a-specific-worker-for-a-project.md">Reserve a specific worker for a project</A>. You can also add workers to a project team in the <STRONG>Work breakdown structure</STRONG> form when you assign workers to tasks.</P>



## What do you want to do?

Learn more about...

Define the qualifications that are required for a project role in a project role template

Specify the types of roles that are required for a project

Book workers for a project team

Convert soft-booked hours to hard-booked hours in the Projects form in AX 2012 R3

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About resource management for projects](about-resource-management-for-projects.md)

 

## Define the qualifications that are required for a project role in a project role template

A project role represents the qualifications that you require for a project. For example, for a software development project, you might have to find workers who have filled certain roles in the past, such as business analyst, software developer, tester, database administrator, graphic designer, or technical writer. In a role type template, you can define the qualifications that are required for each role. You can then add one or more of these roles to your project.

1.  Click **Project management and accounting** \> **Setup** \> **Resource scheduling** \> **Project role templates**.

2.  Click **New**.

3.  In the **Role** field, enter a name to identify the type of project team member role that you are filling.

4.  In the **Description** field, enter a brief summary of the role’s purpose or scope.

5.  Optional: On the **Skills** FastTab, click **Add**, and then, in the **Skill** field, select the name of a skill that is required for this role. Repeat this step for each skill that you want to add.

6.  Optional: On the **Education** FastTab, click **Add**, and then, in the **Education** field, select the name of an educational degree or experience that is required for this role. Repeat this step for each education-related qualification that you want to add.

7.  Optional: On the **Certifications** FastTab, click **Add**, and then, in the **Certificate type** field, select the name of a certificate or certified skill that is required for this role. Repeat this step for each certification that you want to add.

Back to top

 

## Specify the types of roles that are required for a project

Use the following procedure to specify the qualifications that are required to fill the roles that you have defined for a project team. The role types that you can add to a project’s requirements are set up in the **Project role templates** form. In versions of AX 2012 prior to cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can also rank the relative importance of each type of requirement.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open the project that you want to create a project schedule for.

2.  On the **Project team and scheduling** FastTab, click **Add roles**.

3.  In the **Add roles to project** form, in the **Role template** field, select the name of a role type to include on your project team.

4.  In the **Number of workers** field, enter the number of workers to assign to this role type.

5.  Depending on the version of Microsoft Dynamics AX you are using, do one of the following:
    
      - In cumulative update 7 for Microsoft Dynamics AX 2012 R2: If you want the **Worker reservation** form to open immediately after you click **OK**, select the **Book workers immediately** check box.
    
      - In Microsoft Dynamics AX 2012 R3: If you want the **Worker booking** form to open immediately after you click **OK**, select the **Book workers immediately** check box.
    
    The **Worker reservation** form and **Worker booking** form are used to search for qualified workers who have available time to work on the project. The forms are also used to hard book or soft book the workers’ time to the project.

6.  Click **OK**.

Back to top

 

## Book workers for a project team

Use this procedure to book workers for a project for specific days, weeks or months. This procedure assumes that you have defined role type requirements for a project, as explained in the procedure [Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7](key-tasks-create-a-schedule-based-on-a-project-in-ax-2012-r3-or-ax-2012-r2-cu7.md) earlier in this topic.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open the project that you want to create a schedule for.

2.  On the **Project team and scheduling** FastTab, click the row for a project role, and then, depending on the version of Microsoft Dynamics AX you are using, do one of the following:
    
      - In cumulative update 7 for Microsoft Dynamics AX 2012 R2: Click **Reserve worker**.
    
      - In Microsoft Dynamics AX 2012 R3: Click **Book worker**.

3.  In the **Project role** field, confirm that the type of project role that you want to make an assignment for is selected.

4.  Use the **Start date** and **End date** fields to specify the date range during which to schedule a worker.

5.  In the **Format for date range view** list, select the unit of time for which to view worker availability, such as **Weeks**.

6.  Optional: If you want the search results to indicate how many hours are available in the worker’s calendar for the period that you selected, select the **Display remaining capacity** check box.

7.  Optional: In AX 2012 R3, if you want to display text descriptions, in addition to colors, in the availability grid, select the **Display availability descriptions** check box.

8.  Optional: If you want to include worker qualifications as part of your search criteria, follow these steps:
    
    1.  On the **Worker search criteria** FastTab, use the **Skills**, **Project experience**, **Certifications**, **Education**, and **Role** tabs to add qualifications that you want to include in your search criteria.
    
    2.  In the **Minimum percentage for skills match** field, enter a number between 0.01 and 100 to indicate how much the worker qualifications that you entered should matter in your search.
    
    3.  If you want to search only for workers who are employed by the company for which you’re staffing a project, select the **Search for workers hired by the current legal entity** check box.
    
    4.  In AX 2012 R3 only: If you want to search for workers according to the department they work in, select the **Search for workers working in the project department** check box.
    
    5.  Click **Search**.

9.  Optional: If you want to filter your search results further, follow one or more of these steps:
    
      - In the **Worker** field, enter all or part of the name of a specific worker to view.
    
      - In cumulative update 7 for Microsoft Dynamics AX 2012 R2: In the **Company** field, select the name of the legal entity to which to limit your search.
        
        –or–
        
        In AX 2012 R3: In the **Legal entity** field, click the arrow, select the check boxes of the legal entities to which you want to limit your search, and then click **OK**.
    
      - In the **Department** field, select the name of the department to which to limit your search. The options in this field are derived from the Department dimension for your legal entity.

10. In the search results, review the list of workers who are available to work during the requested period. If you searched for a specific worker, information about that worker is displayed. Otherwise, the list includes all workers who are available to work during the date range that you specified.
    

    > [!TIP]
    > <P>To view basic personnel details about a work, point to the worker’s name.</P>

    
    Each line in the search results includes information about the worker’s legal entity, hourly price, and current booking hours, and also includes a graphical view of the worker’s current availability. The graphical schedule indicates whether a worker is available, partially available, or fully booked by using colors and, optionally in AX 2012 R3, text descriptions.

11. Click the cell of each available period for which to hard book or soft book workers to a project.
    
    You can click one or multiple cells for a worker, and you can click cells for one or more workers.

12. Depending on whether you want to reserve or only tentatively reserve time on each worker’s calendar, select one of the following options at the bottom of the **Worker reservation** form:
    
      - Click **Hard book** to create a hard-booked assignment for the worker.
    
      - Click **Soft book** to create a soft-booked, or tentative, assignment for the worker.
    

    > [!NOTE]
    > <P>In the <STRONG>Projects</STRONG> form, on the <STRONG>Project team and scheduling</STRONG> FastTab, you can view a worker’s total hard-booked and soft-booked hours together in a single field. This field indicates the number of hours that the worker is assigned in the work breakdown structure (WBS).</P>
    > <P>In cumulative update 7 for Microsoft Dynamics AX 2012 R2, the total is reported in the <STRONG>Hour reserved</STRONG> field.</P>
    > <P>In AX 2012 R3, the total is reported in the <STRONG>Hours booked</STRONG> field.</P>



13. On the **Hard book** menu or **Soft book** menu, select an option to specify how much of each worker’s time to book. Use the information in the following table to decide which option to select.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Consideration</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Remaining capacity</strong></p></td>
    <td><p>Select this option if a worker’s time is already partially booked and you want to book the rest of the worker’s time in the selected periods.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Full capacity</strong></p></td>
    <td><p>Select this option to book all of a worker’s calendar time in the selected periods.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Capacity percentage</strong></p></td>
    <td><p>Select this option to open the <strong>Worker capacity allocation</strong> form, where you can book a percentage of each worker’s capacity, as represented by unreserved time in the worker’s work calendar.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Specify Hours</strong></p></td>
    <td><p>Select this option to open the <strong>Worker hour allocation</strong> form, where you can book workers for a specific number of hours.</p>
    <p>You can choose to book workers’ first available hours until all hour are assigned, or to distribute hours evenly to workers between their start and end dates.</p></td>
    </tr>
    </tbody>
    </table>


14. Continue to assign workers to projects until you have completed all the assignments that are required.

To cancel an assignment for a worker, click the colored cell that represents the booked time, and then click **Cancel reservation** (in cumulative update 7 for Microsoft Dynamics AX 2012 R2) or **Cancel booking** (in AX 2012 R3).

You can select multiple cells for one or more workers to cancel multiple bookings at the same time.

Back to top

## Convert soft-booked hours to hard-booked hours in the Projects form in AX 2012 R3


> [!NOTE]
> <P>This procedure applies only if AX 2012 R3 in installed.</P>



Use this procedure to easily convert worker hours that were reserved as soft bookings to hard bookings without having to open the **Worker booking** form.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open the project that you want to update a schedule for.

2.  On the **Project team and scheduling** FastTab, select the rows that contain the role assignments for which you want to convert soft-bookings to hard-bookings.
    
    Soft-booked hours are indicated by an asterisk (\*) in the **Hours booked** column.

3.  Click **Confirm hours**.

Back to top

## Find related tasks

[Create a project](create-a-project.md)

[Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012](key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012.md)

[Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 R2](key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012-r2.md)

[Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md)

[Reserve a specific worker for a project](reserve-a-specific-worker-for-a-project.md)

[View booking details (form)](https://technet.microsoft.com/library/dn532267\(v=ax.60\))

  


