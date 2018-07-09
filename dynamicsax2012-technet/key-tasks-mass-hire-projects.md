---
title: 'Key tasks: Mass hire projects'
TOCTitle: 'Key tasks: Mass hire projects'
ms:assetid: ac834d58-a587-4234-94e2-49a1c6fcb8c0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh694715(v=AX.60)
ms:contentKeyID: 42117770
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Key tasks: Mass hire projects [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides key information about mass hire projects, which you can use to hire multiple people at the same time.

## What do you want to do?

Learn more about...

Create a mass hire project

Create positions for a mass hire project

Enter worker information for mass hire positions

Hire a worker for a mass hire position

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About mass hire projects](about-mass-hire-projects.md)

## Create a mass hire project

1.  Click **Human resources** \> **Periodic** \> **Recruitment** \> **Mass hire projects**.

2.  Enter a name for the mass hire project.

3.  Enter a description of the mass hire project.

4.  On the **Project details** FastTab, enter the starting and ending dates for the mass hire project.

5.  Select the worker who is responsible for the mass hire project.

6.  Click **Open project** to open the mass hire project, where you can add positions to the project.

7.  Click **Yes** to confirm the status change for the project.

Back to top

## Create positions for a mass hire project

1.  Click **Human resources** \> **Periodic** \> **Recruitment** \> **Mass hire projects**.

2.  Select the mass hire project to add positions to.

3.  On the **Project positions** FastTab, click **Create positions**.

4.  In the **Create mass hire positions** form, enter the number of workers and positions to create.
    
    For example, if you created the mass hire project to hire seven accountants, enter 7.

5.  In the **Personnel** field group, specify the starting value, interval, and format for the personnel numbers.
    
    This information is used to create personnel numbers for each worker record in the mass hire project. For example, suppose that you want to create personnel numbers with the following pattern: SW-0000, SW-0005, SW-00010. To do this, enter 0 for the starting value, enter 5 for the interval, and then enter SW-\#\#\#\# for the format.
    

    > [!NOTE]
    > <P>If a number sequence code is specified for the personnel number reference in the <STRONG>Human resources shared parameters</STRONG> form in the <STRONG>Number sequence</STRONG> area, you cannot modify the information in these fields.</P>



6.  In the **Positions** field group, specify the starting value, interval, and format for the position IDs.
    
    This information is used to create position IDs for each position record in the mass hire project. For example, suppose that you want to create position IDs with the following pattern: AC-0000, AC-0010, AC-00020. To do this, enter 0 for the starting value, enter 10 for the interval, and then enter AC-\#\#\#\# for the format.
    

    > [!NOTE]
    > <P>If a number sequence code is specified for the position reference in the <STRONG>Human resources shared parameters</STRONG> form in the <STRONG>Number sequence</STRONG> area, you cannot modify the information in these fields.</P>



7.  Select the type of worker record to create when you hire people to fill the positions.

8.  Select the job and department that is associated with the positions.

9.  Enter a description of the positions.

10. Enter a full time equivalent value for the workers. The value 1 indicates full-time employment. Use a number between 0 and 1 to indicate part-time employment.

11. Click **OK**.

Back to top

## Enter worker information for mass hire positions

Before you can hire workers for mass hire positions, you must enter worker information for each position.

1.  Click **Human resources** \> **Periodic** \> **Recruitment** \> **Mass hire projects**.

2.  Select the mass hire project to update.

3.  On the **Project positions** FastTab, select the mass hire position to add worker information to.

4.  Click **Position details**.

5.  Select the type of worker that the person will be. A person can be either an employee or a contractor.

6.  Enter the worker’s name.

7.  Enter the starting and ending dates for the worker if you know the dates. The default starting date is the same as the mass hire project starting date.

8.  Click **Close**.

9.  Repeat steps 3 through 8 for each mass hire position.

Back to top

## Hire a worker for a mass hire position

When you use a mass hire project, position records and worker records are created for the new positions and for the hired people.

1.  Click **Human resources** \> **Periodic** \> **Recruitment** \> **Mass hire projects**.

2.  Select the mass hire project to hire workers for.

3.  On the **Project positions** FastTab, select the mass hire positions to hire workers for.

4.  Click **Hire**.

Back to top

## Find form help

[Mass hire projects (form)](https://technet.microsoft.com/en-us/library/aa591824\(v=ax.60\))

[Create mass hire positions (form)](https://technet.microsoft.com/en-us/library/aa500807\(v=ax.60\))

[Mass hire position details (form)](https://technet.microsoft.com/en-us/library/aa591980\(v=ax.60\))

## Find related tasks

[Key tasks: Workers](key-tasks-workers.md)

[Key tasks: New worker positions](key-tasks-new-worker-positions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

