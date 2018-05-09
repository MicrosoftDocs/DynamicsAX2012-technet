---
title: 'Key tasks: Existing worker positions'
TOCTitle: 'Key tasks: Existing worker positions'
ms:assetid: 9cc83f70-ea9f-49b0-ace7-84c9a0ae161b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ729756(v=AX.60)
ms:contentKeyID: 49564922
ms.date: 09/02/2014
mtps_version: v=AX.60
f1_keywords:
- existing employee
- existing employee position
- existing worker positions
- existing worker position
- existing employees
- existing worker
- existing workers
---

# Key tasks: Existing worker positions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The procedures in this topic describe actions you might take on positions that are already in the system. To view procedures that relate to creating new positions, see [Key tasks: New worker positions](key-tasks-new-worker-positions.md).

## What do you want to do?

Learn more about...

Modify the reporting relationships for a position

Relocate positions to a different department

Retire multiple positions at the same time in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Terminate a worker and retire their position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Place one or more positions on hold at the same time in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About departments, jobs, and positions](about-departments-jobs-and-positions.md)

 

## Modify the reporting relationships for a position

Each position in your organization should have one primary (line) reporting relationship with another position. However, sometimes, such as when an organization uses a matrix organizational structure, positions might also have a secondary (dotted-line) reporting relationship with another position.


> [!NOTE]
> <P>To create dotted-line relationships for positions, you must first create additional position hierarchy types.</P>



### Add a line relationship to a position

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  Select the position to update from the list.

3.  On the **Action Pane**, click **Edit**.

4.  If position actions are enabled by your organization, enter the following information:
    
      - **Personnel action number** – The unique identifier that is assigned to the action. If your organization has not set up personnel action number sequences, enter this number.
    
      - **Personnel action type** – The values for this field are entered in the **Personnel action types** form. Action types of **Modify positions** are displayed.
    
      - **Reason code** – The reason that you are completing the action.
    
    These options are available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the **Personnel actions** configuration key is selected.

5.  On the **General** FastTab, in the **Reports to position** field, select the position that the position should report to.

6.  If position actions are enabled by your organization, click **Complete**. Otherwise, close the form.

### Add a dotted-line relationship to a position

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  Select the position to update from the list.

3.  On the **Action Pane**, click **Edit**.

4.  If position actions are enabled by your organization, enter the following information:
    
      - **Personnel action number** – The unique identifier that was assigned to the action when it was created.
    
      - **Personnel action type** – The values for this field are created in the **Personnel action types** form. Action types of **Modify positions** are displayed.
    
      - **Reason code** – The reason that you are completing the action.
    
    These options are available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the **Personnel actions** configuration key is selected.

5.  On the **Relationships** FastTab, click **Add**.

6.  In the **Hierarchy name** field, select a position hierarchy type to create a relationship for.

7.  Select a position that the position that you selected in step 2 should report to for the hierarchy that you selected.

8.  Complete steps 5 and 6 for each additional relationship.

Back to top

 

## Relocate positions to a different department

Use the **Positions** list page to relocate multiple positions to a different department at the same time.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  Select the positions to relocate.
    

    > [!NOTE]
    > <P>To select multiple rows in a list page at the same time, select the check box for each row or select each row while pressing the Ctrl key.</P>



3.  On the **Action Pane**, click **Mass update**.
    

    > [!TIP]
    > <P>If you are using a version of Microsoft Dynamics AX 2012 that was released before AX 2012 R2, click the <STRONG>Relocate</STRONG> icon on the <STRONG>Action Pane</STRONG>.</P>



4.  Select the **Department** check box.

5.  Select the department to relocate the positions to.

6.  Click **Update**.

Back to top

 

## Retire multiple positions at the same time in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Use the **Positions** list page to retire a position so that it is removed from the system. This also changes the worker assignment end date, if one exists.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  Select the positions to retire.

3.  On the **Action Pane**, in the **Maintain** group, click **Mass update**.

4.  On the **Position duration** tab, select the **Retirement** check box.

5.  Enter the retirement date.

6.  Click **Update**. A message will appear, indicating that the update was successful.

Back to top

 

## Terminate a worker and retire their position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

If you retire a position that has a worker assigned to it, retiring the position terminates the worker at the same time. You can do this only for one worker and one position at a time. If you decide to terminate multiple workers at the same time, you must retire each position individually.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  Double-click the position to terminate the worker relationship and retire the position.

3.  On the **Action Pane**, click **Edit**.

4.  If personnel actions are enabled by your organization, specify the following information:
    
      - **Personnel action number** – The unique identifier that is assigned to the action. If your organization has not set up personnel action number sequences, enter this number.
        
        This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.
    
      - **Personnel action type** – The values for this field are entered in the **Personnel action types** form. Action types of **Modify positions** are displayed.
    
      - **Reason code** – The reason that you are completing the action.
    
      - Click **Continue**.
    
      - On the **Position duration** tab, enter the current date in the **Retirement date** field.
    
      - If your organization uses workflow for this kind of action, you must submit the change for approval before it is completed.
    
      - Click **Complete**.

5.  If position actions are not enabled by your organization, do the following:
    
      - On the **Position duration** tab, select **Retire**.
    
      - Enter the retirement date.
    
      - Click **Retire position**.

Back to top

 

## Place one or more positions on hold at the same time in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Use the **Positions** list page to select one or more positions and put them on hold so that the positions remain active, but workers cannot be assigned to them.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  Select the positions to put on hold.

3.  On the **Action Pane**, in the **Maintain** group, click **Mass update**.

4.  On the **General** tab, select the **Available for assignment** check box.

5.  Enter the date when workers can be assigned to the position. To put the position on hold indefinitely, enter a date that occurs long into the future, such as January 1, 2099.

6.  Click **Update**.

Back to top

## Find form help

[Position hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh242466\(v=ax.60\))

[Position type (form)](https://technet.microsoft.com/en-us/library/hh209577\(v=ax.60\))

## Find related tasks

[Key tasks: Departments](key-tasks-departments.md)

[Key tasks: Jobs](key-tasks-jobs.md)

[Worker and position payroll tasks](worker-and-position-payroll-tasks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

