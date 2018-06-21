---
title: 'Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 R2'
TOCTitle: 'Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 R2'
ms:assetid: 399e100e-51bd-47d0-a6fd-14b3ecb4de4b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ682092(v=AX.60)
ms:contentKeyID: 49655579
ms.date: 10/06/2014
mtps_version: v=AX.60
---

# Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012 R2 [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>The information in this topic applies to Microsoft Dynamics AX 2012 R2 only.</P>
> <P>For information about project-based scheduling in Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack, see <A href="key-tasks-create-a-schedule-based-on-a-project-in-microsoft-dynamics-ax-2012.md">Key tasks: Create a schedule based on a project in Microsoft Dynamics AX 2012</A>.</P>
> <P>For information about project-based scheduling in cumulative update 7 for Microsoft Dynamics AX 2012 R2, see <A href="key-tasks-create-a-schedule-based-on-a-project-in-ax-2012-r3-or-ax-2012-r2-cu7.md">Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7</A>.</P>



By using project-based scheduling, you can assign workers to a project or activity. You can specify the attributes, experience, and availability that workers must have to fill project roles, and then assign a worker to a project or activity based on the project requirements and the worker’s qualifications.

## What do you want to do?

Learn more about...

Specify resource requirements for a project or activity

Review details about a worker’s availability, skill fit, and current assignments

Assign a worker to a project or activity

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About resource management for projects](about-resource-management-for-projects.md)

## Specify resource requirements for a project or activity

Use the following procedures to specify resource requirements for skills, project experience, certifications, education, or other attributes. You can also rank the relative importance of each type of requirement.

### Specify requirements for skills, project experiences, certifications, or education

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project to create a project schedule for.

2.  On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Assign resources**.

3.  In the **Assign resources** form, on the **Resource search criteria** FastTab, click the tab for the worker attribute for which you want to specify a requirement, and then click **Add**.

4.  In the first column, select the attribute that you want to include in the search for resources.

5.  On the **Project experience** tab only: In the **Role** field, select the title of a project role. This indicates that you want to find the specific worker or workers who held this role in the project that you selected in **Project ID** column.

6.  Select the **Required** check box if the worker must possess this attribute in order to be included in the resource search results.

7.  In the **Priority** column, select an option to indicate how heavily you want this attribute weighted against other attributes of the same type. For example, if the attribute is most important, select **6 - Most**. If it is only moderately important, select **3**.

8.  After you finish specifying search criteria for attributes, in the **Competency weighting** field group, assign a number to each attribute type to indicate how heavily it should be weighted in the search for available resources.
    
    For example, if the education requirements that you specified are most important, select **6 - Most** in the **Education** field. If the other worker attributes that you specified should be considered, but are the least important, select **1 - Least**.

9.  Click **Search**.

### Specify requirements for other worker attributes

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project to create a project schedule for.

2.  On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Assign resources**.

3.  In the **Assign resources** form, on the **Resource search criteria** FastTab, on the **Other worker attributes** tab, click **Add**.

4.  In the **Attribute group** column, select the attribute group that includes the additional skills that are required for a worker who is assigned to the project or activity.

5.  In the **Attribute ID** column, select the attribute that is required for a worker who is assigned to the project or activity.

6.  Select the **Required** check box if the worker must possess the selected attribute in order to be included in the resource search results.

7.  In the **Priority** column, select an option to indicate how heavily you want this attribute weighted against other attributes of the same type. For example, if the attribute is most important, select **6 - Most**. If it is only moderately important, select **3**.

8.  After you finish specifying attribute search criteria, in the **Competency weighting** field group, assign a number to each attribute type to indicate how heavily it should be weighted in the search for available resources.
    
    For example, if the education requirements that you specified are most important, select **6 - Most** in the **Education**. If the other worker attributes that you specified should be considered, but are the least important, select **1 - Least**.

9.  Click **Search**.

Back to top

## Review details about a worker’s availability, skill fit, and current assignments

Use this procedure to analyze how well a worker meets the requirements of a project or activity assignment.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project to create a schedule for.

2.  On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Assign resources**.

3.  In the **Assign resources** form, on the **Resources** FastTab, in the **Best resource matches** grid, review the list of workers who are available to work during the requested time period. The list shows the match of the worker’s availability and skills to the requirements of the project, shown as percentages, and the worker’s cost price.

4.  Select a worker to review their details.

5.  To view details of all of the worker’s current assignments, click **Assignment details**. To view a list of all the selected worker’s competencies, click **Resource competencies**.

6.  In the **Resource assignment details for:** grid, review details about the days that the worker is available for the project, and how many hours they are available for each day.

Back to top

## Assign a worker to a project or activity

Use this procedure to assign a worker to specific days for a project. This procedure assumes that you have defined all the activity requirements and selected a worker who you want to assign to the activity.

Each line in the **Resource assignment details for:** grid shows information about a day that requires a worker for an activity. You can assign a worker to as many days as the worker is available, but you cannot exceed the worker’s available capacity.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project to create a schedule for.

2.  On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Assign resources**.

3.  In the **Assign resources** form, on the **Resources** FastTab, in the **Resource assignment details for:** grid, review the activity dates for days that the selected worker is available. The **Availability status** field indicates whether the worker can be scheduled for that day. The following information about the activity is provided:
    
      - The date and day of the activity
    
      - The number of hours that the worker has available that day
    
      - The number of hours for which the worker has a hard or soft commitment on that day
    
      - The total number of hours that the worker is available to work on that day

4.  Select an assignment line, click **Assign**, and then select the type of assignment that you want to make for the worker:
    
      - **Full worker capacity** – Assign all the selected worker’s available hours to the project as hard-booked hours.
    
      - **Hour entries to hard** – Create a hard assignment for the worker.
    
      - **Hour entries to soft** – Create a soft, or tentative, assignment for the worker.

5.  If you want to assign a different number of hours to the worker for that day, change the hours in the **Hour entry** column to the number of hours that you want to assign to the worker.

6.  After you assign a worker to the project or activity, review the following changes on the activity line:
    
      - The number of hours in the **Hard-booked hours** or **Soft-booked hours** column changes to the number of hours that you assigned to the worker, depending on the type of commitment that you selected.
    
      - The number of hours in the **Available capacity in hours** column is reduced by the number of hours that you assigned to the worker.

7.  Continue assigning activities to the worker until you have completed all of the assignments that are required.

8.  Click the **Release** or **Transfer** button to change an assignment for a worker. Use these buttons to do the following:
    
      - **Release** – Select the line of the activity for which the worker has an assignment that you want to remove, and then click **Release**. In the list, click **Soft bookings** to remove a tentative assignment to the project or activity, click **Hard bookings** to remove a firm assignment to the project or activity, or click **All bookings** to remove all assignments from the project or activity.
    
      - **Transfer** – Depending on whether you want to convert all or only some soft bookings to hard bookings, do one of the following:
        
          - If you want to convert all soft booking hours that have already been assigned to hard bookings, click **Transfer**, and then click **All**.
        
          - If you want to convert only some of the soft booking hours to hard bookings, select a line for which soft bookings have been assigned, click **Transfer**, and then click **Soft bookings to hard bookings**. Repeat this step for each line that you want to transfer to a hard booking.

Back to top

## Find form help

[Schedule resources (form)](https://technet.microsoft.com/en-us/library/hh209507\(v=ax.60\))

[Assign resources (form)](https://technet.microsoft.com/en-us/library/hh208809\(v=ax.60\))

[Worker (form)](https://technet.microsoft.com/en-us/library/hh209054\(v=ax.60\))

[Other worker attributes (form)](https://technet.microsoft.com/en-us/library/hh242802\(v=ax.60\))

[Work breakdown structure (form)](https://technet.microsoft.com/en-us/library/hh209089\(v=ax.60\))

## Find related tasks

[Specify basic project schedule details](specify-basic-project-schedule-details.md)

[Key tasks: Assign workers to projects based on availability](key-tasks-assign-workers-to-projects-based-on-availability.md)

[About resource management for projects](about-resource-management-for-projects.md)

[Microsoft Dynamics AX 2012 R2 – Resource scheduling in Project management and accounting](http://go.microsoft.com/fwlink/?linkid=268038%26amp%3bclcid=0x409)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

