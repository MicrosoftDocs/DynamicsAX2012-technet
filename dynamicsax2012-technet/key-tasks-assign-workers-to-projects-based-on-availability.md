---
title: 'Key tasks: Assign workers to projects based on availability'
TOCTitle: 'Key tasks: Assign workers to projects based on availability'
ms:assetid: 4e390353-cec1-4cd3-b1d1-de67f216adef
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208763(v=AX.60)
ms:contentKeyID: 36057047
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- resource-based scheduling
- worker attributes
- worker availability
- hard commitments
- project schedule
- resource assignment
- resource availability
- soft commitments
- worker assignment
- worker skills
---

# Key tasks: Assign workers to projects based on availability 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to staff a project based on the skills and availability of worker resources. By using resource-based scheduling, you can deploy your organization's workers efficiently and effectively when they are needed. You can review the capacity of each worker and see whether the worker is being adequately scheduled, and then assign the worker to a project or activity based on the project requirements and the worker’s qualifications.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can also staff a project by searching for specific workers first and then assigning them to the project. For more information, see <A href="reserve-a-specific-worker-for-a-project.md">Reserve a specific worker for a project</A>.</P>



## What do you want to do?

Learn more about...

Identify a worker and view project experience and other attributes

Identify a worker and view project experience and other attributes in cumulative update 7 for Microsoft Dynamics AX 2012 R2

Select a project or activity and assign the worker

Assign a worker to a project or activity

Assign a worker to a project or activity in Microsoft Dynamics AX 2012 R2

Assign a worker to a project in cumulative update 7 for Microsoft Dynamics AX 2012 R2

Review project activity requirements

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About resource management for projects](about-resource-management-for-projects.md)

 

## Identify a worker and view project experience and other attributes

Use this procedure to identify a worker for a project or activity based on the availability of the worker, or to assign a specific worker to a project or activity, in the **Schedule resources** form.

1.  Click **Project management and accounting** \> **Periodic** \> **Resource scheduling** \> **Schedule resources**.

2.  Choose one of the following methods to locate an available worker or workers:
    
      - Use the **Start date** and **End date** fields to specify the date range in which you want to schedule a worker. In the **Worker** field, select the worker who you want to schedule, and then click **Search**.
        
        If the worker is available, you can review information about the worker, such as their education, skills, and project experience, on the **Resources** FastTab. In addition, on the **Projects** FastTab, you can view information about projects and activities that match the selected worker’s competencies and availability for the time frame that you entered.
    
      - Use the **Start date** and **End date** fields to specify the date range in which you want to schedule a worker, but do not select a worker, and then click **Search**.
        
        A list of workers who are available to work during the requested time period is displayed on the **Resources** FastTab.
    
      - In the **Worker** field, select the worker whom you want to schedule, but do not specify a date range. Click **Search**.
        
        Information about the worker is displayed on the **Resources** FastTab. In addition, the list of projects on the **Projects** FastTab includes all projects and activities that must schedule workers.

3.  On the **Resources** FastTab, review the list of workers who are available to work during the requested time period. If you searched for a specific worker, information about that worker is displayed. Otherwise, the list includes all workers who are available to work during the date range that you specified.

4.  Review a worker’s competencies on the tabs on the **Resources** FastTab. The tabs include the following:
    
      - The **Overview** tab, which displays the current percentage of a worker’s commitment to projects or activities.
    
      - The **Skills** tab, which displays a list of the worker’s skills, such as languages spoken or knowledge of software programs.
    
      - The **Project experience** tab, which displays a list of projects on which the worker has experience and the role that the worker had on the project.
    
      - The **Certifications** tab, which displays a list of the certificates that the worker has earned.
    
      - The **Education** tab, which displays the types of education that the worker has completed.
    
      - The **Other worker attributes** tab, which displays a list of additional attributes that the worker has, such as public speaking skills.

5.  In the list on the **Overview** tab, select the worker whom you want to assign to a project.

Back to top

 

## Identify a worker and view project experience and other attributes in cumulative update 7 for Microsoft Dynamics AX 2012 R2

Use this procedure to identify a worker for a project based on the availability and qualifications of the worker, or to assign a specific worker to a project, on the **Resource availability** list page.

1.  Click **Project management and accounting** \> **Common** \> **Project resources** \> **Resources**.

2.  Use the **Start date** and **End date** fields to specify the date range in which to schedule a worker.

3.  In the **Format for date range view** list, select the unit of time for which to view worker availability, such as **Weeks**.

4.  Optional: If you want the search results to indicate how many hours are available in the worker’s calendar for the period that you selected, select the **Display remaining capacity** check box.

5.  Optional: If you want to include worker qualifications as part of your search criteria, follow these steps:
    
    1.  On the **Worker search criteria** FastTab, use the **Skills**, **Project experience**, **Certifications**, **Education**, and **Role** tabs to add any qualifications that you want to include in your search critiera.
    
    2.  In the **Minimum percentage for skills match** field, enter a number between **0.01** and **100** to indicate how strongly the worker qualifications that you entered should be factored into your search.
    
    3.  If you want to search only for workers who are employed by the company for which you’re staffing a project, select the **Search for workers hired by the current legal entity** check box.
    
    4.  Click **Search**.

6.  Optional: If you want to filter your search results further, follow one or more of these steps:
    
      - In the **Worker** field, enter all or part of the name of a specific worker to view.
    
      - In the **Company** field, select the name of the legal entity to which to limit your search.
    
      - In the **Department** field, select the name of the department to which to limit your search. The options in this field are derived from the Department dimension for your legal entity.

7.  In the search results, review the list of workers who are available to work during the requested period. If you searched for a specific worker, information about that worker is displayed. Otherwise, the list includes all workers who are available to work during the date range that you specified.
    

    > [!TIP]
    > <P>To view basic personnel details about a work, point to the worker’s name. To view the worker’s complete personnel record, double-click the worker’s name.</P>



8.  If you want to review the details of a worker’s qualifications, on the **Competencies** tab, click the following buttons:
    
      - **Skills** – View a list of the worker’s skills, such as languages that the worker speaks or the worker’s knowledge of software programs.
    
      - **Certificates** – View a list of the certificates that the worker has earned.
    
      - **Project experience** – View a list of projects on which the worker has experience and the role that the worker had on the project.
    
      - **Education** – View a list of the types of the education programs that the worker has completed.

Back to top

 

## Select a project or activity and assign the worker

Use this procedure to find a project that is the best match for the selected worker. This is a continuation of [Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md) procedure earlier in this topic. It assumes that you have searched for a worker, a time frame, or both, and have selected the worker that you want to assign from the list of available workers.

The projects and activities that are displayed are scheduled during the date range that you specified, if one was specified. The projects and activities that are displayed also require workers who are available during the date range to complete the work. Select the project or activity based on the competencies defined for the worker and the requirements of the project.

The projects or activities are displayed in a list that reflects how well the worker’s skills and availability match the requirements for the project or activity. They are listed in the following order of priority:

1.  Projects or activities whose requirements exactly match the skills and availability of the worker.

2.  Projects or activities whose requirements partially match the skills and availability of the worker.

3.  Projects or activities whose requirements do not match the skills and availability of the worker.

Review the list of projects and activities and select the one that you want to assign the worker to.

1.  On the **Projects** FastTab, review the list of projects and activities that need a worker. The information that is displayed about the project or activity includes the following:
    
      - A description of the project and of the activity.
    
      - The length of time, in days, that is required to complete the project.
    
      - The start date and end date of the project.
    
      - The effort, or number of hours, that is required to complete the project.
    
      - The percentage of the worker’s skills that match the project requirements.
    
      - The percentage of the worker’s availability that matches the project requirements.
        
        Depending on the requirements of the project and the information that you have about the worker, you can determine the project or activity that you want to assign the worker to.

2.  Select the project or activity to which you want to assign the worker by clicking the line that contains the project information.

3.  The **Assignments** FastTab now displays the dates and activities to which you can assign the worker.

4.  Review the worker’s availability for the selected project on the **Assignments** FastTab to determine whether they are available on the dates scheduled for the project or activity.

5.  If the worker is not available for the project or activity, select another project and review the projects until you find one that meets the worker’s availability.

Back to top

 

## Assign a worker to a project or activity

Use this procedure to assign the project or activity that is the best match for the selected worker. This is a continuation of the [Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md) procedure earlier in this topic. It assumes that you have selected a worker and selected a project or activity.

Each line on the **Assignments** FastTab shows information about each day of the activity that requires a worker. You can assign a worker to as many days as the worker is available, but you cannot exceed the worker’s available capacity.

You can view whether a worker has a hard or soft commitment for a project or activity, if the worker is available for that day, or if they have a conflict.

1.  On the **Assignments** FastTab, review the dates for activities for which you must have a worker. The color of the activity line indicates whether the worker can be scheduled for that day. Information about the activity includes:
    
      - The date and day of the activity.
    
      - The number of hours that are required to complete the activity for the day.
    
      - The number of hours that the worker is available that day.
    
      - The number of hours for which the worker has a hard or soft commitment on that day.
    
      - The total number hours that the worker is available to work on that day.

2.  Select the project or activity, and then click **Assign**. In the drop-down list, select the type of assignment that you want to make for the worker.
    
      - Click **Soft** to create a soft-booked, or tentative, assignment for the worker.
    
      - Click **Hard** to create a hard-booked assignment for the worker.

3.  To change the number of hours that you want to assign to the worker, enter a new value in the **Activity effort requirements (hours)** column.

4.  After you have assigned a worker to the project or activity, review the following changes on the activity line:
    
      - The activity line changes color to show that the worker is not available or only partially available on that day.
    
      - The number of hours in the **Hard commitment (hours)** or **Soft commitment (hours)** column changes to the number of hours that you assigned to the worker, depending on the type of commitment that you selected.
    
      - The number of hours in the **Worker available capacity (hours)** column is reduced by the number of hours that you assigned to the worker.

5.  Continue assigning activities to the worker until you have completed all of the assignments that are required.

6.  To change an assignment for a worker, use the **Release** and **Transfer** buttons.
    
      - **Release** – Select the check box next to a project or activity for which the worker has an assignment that you want to remove, and then click **Release**. In the list, click **Soft** to remove the soft-booked assignment from the project or activity, or click **Hard** to remove the hard-booked assignment from the project or activity. The list selection that is enabled is the same as the type of assignment that is being released.
    
      - **Transfer** – Select the check box next to a project or activity for which the worker has an assignment that you want to transfer, and then click **Transfer**. In the list, click **Soft commitments to hard commitments** or **Hard commitments to soft commitments** to change the type of assignment to the project or activity. The list selection that is enabled is the same as the type of assignment that is being transferred.

7.  After you finish assigning the worker to activities, click **Save** to save the worker assignments.

Back to top

 

## Assign a worker to a project or activity in Microsoft Dynamics AX 2012 R2

Use this procedure to assign the project or activity that is the best match for the selected worker. This is a continuation of the [Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md) procedure earlier in this topic. It assumes that you have selected a worker and selected a project or activity.

Each line on the **Assignments** FastTab shows information about each day of the activity that requires a worker. You can assign a worker to as many days as the worker is available, but you cannot exceed the worker’s available capacity.

You can view whether a worker has a hard or soft commitment for a project or activity, if the worker is available for that day, or if they have a conflict.

1.  On the **Assignments** FastTab, review the activity for activities for which you must have a worker. The color of the activity line indicates whether the worker can be scheduled for that day. Information about the activity includes:
    
      - The date and day of the activity.
    
      - The number of hours that are required to complete the activity for the day.
    
      - The number of hours that the worker is available that day.
    
      - The number of hours for which the worker has a hard or soft commitment on that day.
    
      - The total number hours that the worker is available to work on that day.

2.  Select the project or activity, and then click **Assign**. In the drop-down list, select the type of assignment that you want to make for the worker.
    
      - Click **Soft** to create a soft-booked, or tentative, assignment for the worker.
    
      - Click **Hard** to create a hard-booked assignment for the worker.

3.  To change the number of hours that you want to assign to the worker, change the value in the **Hour entry** column.

4.  After you assign a worker to the project or activity, the status in the **Availability status** field changes to show that the worker is not available or only partially available on that day.

5.  Continue assigning activities to the worker until you have completed all of the assignments that are required.

6.  To change an assignment for a worker, use the **Release** and **Transfer** buttons.
    
      - **Release** – Select the line of the activity for which the worker has an assignment that you want to remove, and then click **Release**. In the list, click **Soft bookings** to remove the tentative assignment to the project or activity, click **Hard bookings** to remove the firm assignment to the project or activity, or click **All bookings** to remove all assignments from the project or activity.
    
      - **Transfer** – Select the line of the project or activity for which the worker has an assignment that you want to transfer, and then click **Transfer**. In the list, click **All** to convert all soft bookings to hard bookings, or **Soft bookings to hard bookings** to convert only the soft bookings that have been entered to hard bookings.

Back to top

 

## Assign a worker to a project in cumulative update 7 for Microsoft Dynamics AX 2012 R2

Use this procedure to assign qualified and available workers to projects that have open roles on the project team. This is a continuation of the [Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md) procedure earlier in this topic. This procedure assumes that you have performed a query for qualified and available workers, and that you are viewing the search results on the **Resource availability** list page.

Each line in the search results includes information about the worker’s legal entity, hourly price, and current booking hours, and also includes a graphical view of the worker’s current availability. The graphical schedule view uses colors to indicate whether a worker is available, partially available, or fully booked.

1.  Click the colored cell of each available period for which to hard book or soft book workers to a project.
    
    You can click one or multiple cells for a worker, and you can click cells for one or more workers.

2.  Depending on whether you want to reserve or only tentatively reserve time on each worker’s calendar, select one of the following options at the bottom of the **Resource availability** list page:
    
      - Click **Hard book** to create a hard-booked assignment for the worker.
    
      - Click **Soft book** to create a soft-booked, or tentative, assignment for the worker.
    

    > [!NOTE]
    > <P>In the <STRONG>Projects</STRONG> form, a worker’s total hard-booked and soft-booked hours are reported together in the <STRONG>Hours booked</STRONG> field on the <STRONG>Project team and scheduling</STRONG> FastTab. The <STRONG>Hours assigned</STRONG> field indicates the number of hours that the worker is assigned in the work breakdown structure.</P>



3.  On the **Hard book** menu or **Soft book** menu, select an option to specify how much of each worker’s time to book. Use the following table to decide which option to select.
    
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
    <td><p>Select this option to book a percentage of each worker’s capacity, as represented by unreserved time in the worker’s work calendar.</p></td>
    </tr>
    </tbody>
    </table>


4.  In the **Project selection** form, select the line of the project for which to book the selected workers.

5.  If you selected **Capacity percentage** in step 3, enter the percentage of each worker’s available time to book on this project.

6.  Click **OK**.

7.  Continue to assign workers to projects until you have completed all the assignments that are required.

To cancel an assignment for a worker, click the colored cell that represents the booked time, and then click **Cancel booking**.

You can select multiple cells for one or more workers to cancel multiple bookings at the same time.

Back to top

 

## Review project activity requirements

Requirements for the project that you selected on the **Projects** FastTab, such as worker education or project experience, are displayed on the **Project activity requirements** FastTab.


> [!NOTE]
> <P>How you review project activity requirements depends on which version of Microsoft Dynamics AX 2012 you are using.</P>
> <P>In Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack, project requirements are first entered in the <STRONG>Projects</STRONG> form, on the <STRONG>Project requirements</STRONG> FastTab.</P>
> <P>In Microsoft Dynamics AX 2012 R2, they are entered in the <STRONG>Assign resources</STRONG> form, on the <STRONG>Resource search criteria</STRONG> FastTab.</P>
> <P>This control is available only in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>In cumulative update 7 for Microsoft Dynamics AX 2012 R2, project activity requirements are managed in the work breakdown structure (WBS) for a project. For more information, see <A href="about-work-breakdown-structures.md">About work breakdown structures</A> and <A href="create-a-work-breakdown-structure-of-tasks-for-a-project.md">Create a work breakdown structure of tasks for a project</A>.



The different types of requirements for the project or activity are displayed on the following tabs:

  - **Skills** – The skill requirements for the project or activity, such as languages spoken or knowledge of software programs.

  - **Project experience** – The projects on which the worker should have experience to be assigned to the project or activity.

  - **Certifications** – The certification requirements for the project or activity.

  - **Education** – The level of education that is required for a worker to be assigned to the project or activity.

  - **Other worker attributes** – The requirements for additional worker attributes for the project or activity, such as public speaking.

You can review the requirements for the project or activity to make sure that the worker assignment is the optimal match for the worker and for the project or activity.

Back to top

## Find form help

[Assign resources (form)](https://technet.microsoft.com/en-us/library/hh208809\(v=ax.60\))

[Schedule resources (form)](https://technet.microsoft.com/en-us/library/hh209507\(v=ax.60\))

[Other worker attributes (form)](https://technet.microsoft.com/en-us/library/hh242802\(v=ax.60\))

[Worker (form)](https://technet.microsoft.com/en-us/library/hh209054\(v=ax.60\))

[Work breakdown structure (form)](https://technet.microsoft.com/en-us/library/hh209089\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

## Find related tasks

[Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012](key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012.md)

[Microsoft Dynamics AX 2012 R2 – Resource scheduling in Project management and accounting](http://go.microsoft.com/fwlink/?linkid=268038%26amp%3bclcid=0x409)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

