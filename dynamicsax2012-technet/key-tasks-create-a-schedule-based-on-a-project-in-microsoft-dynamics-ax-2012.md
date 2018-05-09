---
title: 'Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012'
TOCTitle: 'Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012'
ms:assetid: dd3cb698-22af-4b4f-9264-f68f307344b3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227409(v=AX.60)
ms:contentKeyID: 36059681
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project add-in
- project-based scheduling
- hard commitments
- resource availability
- soft commitments
- worker skills
- resources assignment
---

# Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>The information in this topic applies to Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack.</P>
> <P>For information about project-based scheduling in Microsoft Dynamics AX 2012 R2, see <A href="key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012-r2.md">Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 R2</A>.</P>
> <P>For information about project-based scheduling in cumulative update 7 for Microsoft Dynamics AX 2012 R2, see <A href="key-tasks-create-a-schedule-based-on-a-project-in-ax-2012-r3-or-ax-2012-r2-cu7.md">Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7</A>.</P>



In Microsoft Dynamics AX, you can schedule resources based on the requirements and schedule of a project or by the skills and availability of workers. By using project-based scheduling, you can assign workers to a project or activity. You can specify the attributes, experience, and availability that workers must have to fill project roles, and then assign a worker to a project or activity based on the project requirements and the worker’s qualifications.

## What do you want to do?

Learn more about...

Show available resources

Review activity requirements

Identify a worker and view project experience and other attributes

Assign the selected worker to the project or activity

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About resource management for projects](about-resource-management-for-projects.md)

## Show available resources

Use this procedure to get started with the process of finding workers for a project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. On the **Projects** page, on the **Action pane**, on the **Plan** tab, in the **Activities** group, click **Assign resources**.

2.  In the **Assign resources** form, review the project or activity information in the **General** section.

3.  Click **Show available resources** to display information about the activity requirements and the workers who are available to work on the project or activity.

Back to top

## Review activity requirements

Requirements for the project or activity, such as worker education or project experience, are displayed on the **Activity requirements** FastTab. Activity requirements are first entered in the **Projects** form, on the **Project requirements** FastTab. The following tabs show the different types of requirements for the project or activity:

  - **Education** – The level of education that is required for a worker to be assigned to the project or activity.

  - **Skills** – The skill requirements for the project or activity, such as languages spoken or knowledge of software programs.

  - **Certification** – The certification requirements for the project or activity.

  - **Project experience** – The projects on which the worker should have experience to be assigned to the project or activity.

  - **Other worker attributes** – The requirements for additional worker attributes for the project or activity, such as public speaking.

Review the requirements for the project or activity to make sure that all the requirements have been added to the project or activity. You can enter any additional requirements on the **Activity requirements** FastTab by clicking **Add line**. You can also update requirements or remove them from the list. To save any changes that you made to the activity requirements, click **Save project requirements**.

Back to top

## Identify a worker and view project experience and other attributes

Use this procedure to review the list of workers on the **Resource availability** FastTab and to identify a worker for the project or activity based on the availability of the worker.

1.  Review the list of workers on the **Resource availability** FastTab who are available to work during the requested time period. The list shows the match of the worker’s attributes and availability to the requirements of the project, shown as a percentage.

2.  Review a worker’s attributes on the tabs on the **Resource Availability** FastTab. The tabs include the following:
    
      - **Overview** – The percentage of a worker’s attributes and commitment to projects or activities that match the requirements of the project.
    
      - **Education** – The types of education that have been completed by the worker.
    
      - **Skills** – A list of the worker’s skills, such as languages spoken or knowledge of software programs.
    
      - **Certification** – A list of the certificates that the worker has earned.
    
      - **Project experience** – A list of projects on which the worker has experience and the role that the worker had on the project.
    
      - The **Other worker attributes** – A list of additional attributes that the worker has, such as public speaking skills.

3.  Select the worker that you want to assign to the project from the list on the **Overview** tab.

4.  View detailed information about the selected worker’s assignments and availability on the **Assignments** FastTab.

Back to top

## Assign the selected worker to the project or activity

Use this procedure to assign the worker that you selected in the previous procedure to specific days for the project. This procedure assumes that you have defined all the activity requirements and selected a worker who you want to assign to the activity.

Each line on the **Assignments** FastTab shows information about each day of the activity that requires a worker. You can assign a worker to as many days as the worker is available, but you cannot exceed the worker’s available capacity.

The colors that you set up for the scheduling calendar in the **Project management and accounting parameters** form are displayed on the **Assignments** FastTab. The colors indicate whether a worker has a hard or soft commitment for a project or activity, the worker is available for that day, or the worker has a conflict.

1.  Review the activity dates on the **Assignments** FastTab for days that the worker is available. The color of the activity line indicates whether the worker can be scheduled for that day. Information provided about the activity includes the following:
    
      - The date and day of the activity
    
      - The number of hours that are required to complete the activity for the day
    
      - The number of hours that the worker has available that day
    
      - The number of hours for which the worker has a hard or soft commitment on that day
    
      - The total number hours that the worker is available to work on that day

2.  Select the check box next to an activity, and then click **Assign**. In the list, select the type of assignment to make for the worker.
    
      - Select **Soft** to create a tentative assignment for the worker.
    
      - Select **Hard** to create a firm assignment for the worker.

3.  If you want to assign the worker to a different number of hours for that day, you can change the hours in the **Activity effort requirement** column to the number of hours that you want to assign to the worker.

4.  After you assign a worker to the project or activity, review the following changes on the activity line:
    
      - The activity line changes color to show that the worker is not available or only partially available on that day.
    
      - The number of hours in the **Hard commitment (hours)** or **Soft commitment (hours)** column changes to the number of hours that you assigned to the worker, depending on the type of commitment that you selected.
    
      - The number of hours in the **Worker available capacity (hours)** column is reduced by the number of hours that you assigned to the worker.

5.  Continue assigning activities to the worker until you have completed all of the assignments that are required.

6.  If you must make a change to an assignment for a worker, you can use the **Release** or **Transfer** button to make these changes. Use these buttons to perform the following activities:
    
      - **Release** – Select the line of the activity for which the worker has an assignment that you want to remove, and then click **Release**. In the list, click **Soft bookings** to remove a tentative assignment to the project or activity, click **Hard bookings** to remove a firm assignment to the project or activity, or click **All bookings** to remove all assignments from the project or activity.
    
      - **Transfer** – Select the check box next to a project or activity for which the worker has an assignment that you want to transfer, and then click **Transfer**. In the list, click **Soft commitments to hard commitments** or **Hard commitments to soft commitments** to change the type of assignment to the project or activity. The list selection that is enabled is the same as the type of assignment that is being transferred.

7.  After you finish assigning the worker to activities, click **Save** to save the worker assignments.

Back to top

## Find form help

[Schedule resources (form)](https://technet.microsoft.com/en-us/library/hh209507\(v=ax.60\))

[Assign resources (form)](https://technet.microsoft.com/en-us/library/hh208809\(v=ax.60\))

[Worker (form)](https://technet.microsoft.com/en-us/library/hh209054\(v=ax.60\))

[Other worker attributes (form)](https://technet.microsoft.com/en-us/library/hh242802\(v=ax.60\))

[Work breakdown structure (form)](https://technet.microsoft.com/en-us/library/hh209089\(v=ax.60\))

## Find related tasks

[Microsoft Dynamics AX 2012 R2 – Resource scheduling in Project management and accounting](http://go.microsoft.com/fwlink/?linkid=268038%26clcid=0x409)

[Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

