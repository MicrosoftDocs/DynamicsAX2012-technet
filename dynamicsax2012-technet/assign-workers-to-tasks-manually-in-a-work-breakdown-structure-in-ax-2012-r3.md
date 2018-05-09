---
title: Assign workers to tasks manually in a work breakdown structure in AX 2012 R3
TOCTitle: Assign workers to tasks manually in a work breakdown structure in AX 2012 R3
ms:assetid: 8a679501-fd22-4b1b-aba7-0c1ba3ae3c82
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn783115(v=AX.60)
ms:contentKeyID: 62830463
ms.date: 09/05/2014
mtps_version: v=AX.60
---

# Assign workers to tasks manually in a work breakdown structure in AX 2012 R3 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to assign workers to project tasks in the **Work breakdown structure** form. You can assign workers who have already been added to the project team and whose time has already been booked for the project. You can also search for other available workers and assign them to the task. When you assign other available workers, they are automatically added to the project team.

How hours for tasks are distributed to workers depends on whether workers have already been added to the project team. Hours are also distributed differently among these groups when workers are removed from a work breakdown structure (WBS) task. For more information, see [About redistributing manually assigned hours for a work breakdown structure in AX 2012 R3](about-redistributing-manually-assigned-hours-for-a-work-breakdown-structure-in-ax-2012-r3.md).


> [!NOTE]
> <P>You manage the project team on the <STRONG>Project team and scheduling</STRONG> FastTab in the <STRONG>Projects</STRONG> form. For information about how to add workers to a project team, see <A href="key-tasks-create-a-schedule-based-on-a-project-in-ax-2012-r3-or-ax-2012-r2-cu7.md">Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7</A>.</P>



## Assign workers who have been added to the project team

1.  In the **Work breakdown structure** form, select the task to which you want to assign workers.

2.  Click the arrow in the **Workers** field, and then select the check box next to each worker’s name that you want to assign.

3.  Click **OK**.

## Assign workers who have not been added to the project team

1.  In the **Work breakdown structure** form, select the task to which you want to assign workers.

2.  Click the arrow in the **Workers** field, and then click **View more workers** to open the **Worker assignment** form.

3.  In the **Activity name** field, ensure that the activity you want to assign workers to is selected.

4.  In the **Format for date range view** list, select the unit of time for which to view worker availability, such as **Weeks**.

5.  Optional: If you want the search results to indicate how many hours are available in the worker’s calendar for the period that you selected, select the **Display remaining capacity** check box.

6.  Optional: In Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, the available capacity of workers is indicated by colored cells in the **Work breakdown structure** form. In Microsoft Dynamics AX 2012 R3, if you want to display text descriptions, in addition to colors, in the availability grid, select the **Display availability descriptions** check box.

7.  Optional: If you want to include worker qualifications as part of your search criteria, follow these steps:
    
    1.  On the **Worker search criteria** FastTab, use the **Skills**, **Project experience**, **Certifications**, **Education**, and **Role** tabs to add any qualifications that you want to include in your search criteria.
    
    2.  In the **Minimum percentage for skills match** field, enter a number between 0.01 and 100 to indicate how strongly the worker qualifications that you entered should be factored into your search.
    
    3.  If you want to search only for workers who are employed by the company for which you’re staffing a project, select the **Search for workers hired by the current legal entity** check box.
    
    4.  In AX 2012 R3 only: If you want to search for workers according to the department they work in, select the **Search for workers working in the project department** check box.
    
    5.  Click **Search**.

8.  Optional: If you want to filter your search results further, follow these steps:
    
      - In the **Worker** field, enter all or part of the name of a specific worker to view.
    
      - In cumulative update 7 for Microsoft Dynamics AX 2012 R2: In the **Company** field, select the name of the legal entity to which to limit your search.
        
        –or–
        
        In AX 2012 R3: In the **Legal entity** field, click the arrow, select the check boxes of the legal entities to which you want to limit your search, and then click **OK**.
    
      - In the **Department** field, select the name of the department to which to limit your search. The options in this field are derived from the Department dimension for your legal entity.

9.  In the search results, review the list of workers who are available to work during the requested period. If you searched for a specific worker, information about that worker is displayed. Otherwise, the list includes all workers who are available to work during the date range that you specified.
    

    > [!TIP]
    > <P>To view basic personnel details about a worker, point to the worker’s name.</P>

    
    Each line in the search results includes information about the worker’s legal entity, hourly price, and current booking hours and also includes a graphical view of the worker’s current availability. The graphical schedule indicates whether a worker is available, partially available, or fully booked by using colors and, optionally in AX 2012 R3, text descriptions.

10. Click the cell of each available period for which to hard book or soft book workers to a project.
    

    > [!NOTE]
    > <P>When you hard book a worker, you make a firm reservation for the worker in the project. The worker’s time cannot be reserved for other project assignments. When you soft book a worker, you make a tentative reservation for the worker in the project. The worker’s time can still be reserved for other projects.</P>

    
    You can click one or more cells for a worker, and you can click multiple cells for one or more workers.

11. Depending on whether you want to reserve or only tentatively reserve time on each worker’s calendar, select one of the following options at the bottom of the **Worker reservation** form:
    
      - Click **Hard book** to create a hard-booked assignment for the worker.
    
      - Click **Soft book** to create a soft-booked, or tentative, assignment for the worker.
    

    > [!NOTE]
    > <P>In the <STRONG>Projects</STRONG> form, on the <STRONG>Project team and scheduling</STRONG> FastTab, you can view a worker’s total hard-booked and soft-booked hours together in a single field. This field indicates the number of hours that the worker is assigned in the WBS.</P>
    > <P>In AX 2012 R3, the total is reported in the <STRONG>Hours booked</STRONG> field.</P>



12. On the **Hard book** or **Soft book** menu, select an option to specify how much of each worker’s time to book. Use the following table to decide which option to select.
    
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


13. Continue to assign workers to projects until you have completed all the assignments that are required.

To cancel an assignment for a worker, click the colored cell that represents the booked time, and then click **Cancel reservation** (in cumulative update 7 for Microsoft Dynamics AX 2012 R2) or **Cancel booking** (in AX 2012 R3).

You can select multiple cells for one or more workers to cancel multiple bookings at the same time.

## See also

[Create a work breakdown structure of tasks for a project](create-a-work-breakdown-structure-of-tasks-for-a-project.md)

[Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7](key-tasks-create-a-schedule-based-on-a-project-in-ax-2012-r3-or-ax-2012-r2-cu7.md)

[Work breakdown structure (form)](https://technet.microsoft.com/en-us/library/hh209089\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

