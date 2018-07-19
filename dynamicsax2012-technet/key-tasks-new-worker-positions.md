---
title: 'Key tasks: New worker positions'
TOCTitle: 'Key tasks: New worker positions'
ms:assetid: cf6ffc13-11af-4402-b6dd-8781408db244
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242914(v=AX.60)
ms:contentKeyID: 36059479
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- position
- worker
- workers
- new worker
- positions
- worker position
- worker positions
- new position
- new positions
- new workers
- new worker positions
- new worker position
audience: Application User
ms.search.region: Global
---

# Key tasks: New worker positions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can create positions, you must set up reference information that you use for positions. The procedures in this topic are listed in the order in which you should complete them.

You must first set up jobs before you can set up positions. For more information, see [Key tasks: Jobs](key-tasks-jobs.md).

## What do you want to do?

Learn more about...

Set up position types

Set up position hierarchy types

Set up compensation regions for positions

Set up personnel actions in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Create a new position

Create a new position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Create one or more new positions from an existing position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Create one or more new positions from an existing position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3 when personnel actions are enabled

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About departments, jobs, and positions](about-departments-jobs-and-positions.md)

 

## Set up position types

Position types are used to categorize the positions that you have throughout your organization. For example, you might create the following position types: Permanent, Seasonal, and Day labor.

1.  Click **Human resources** \> **Setup** \> **Organization** \> **Position types**.

2.  Click **New**.

3.  Enter a name for the position type and a brief description of the position type.

4.  If you are using cumulative update 6 for Microsoft Dynamics AX 2012 or a later version, in the **Classification of the position type** field, select **Full-time** or **Part-time**.

5.  Repeat steps 2 through 4 for additional position types.

Back to top

 

## Set up position hierarchy types

Create a position hierarchy type for each organizational hierarchy that your organization uses. For example, if your organization uses a matrix structure, you might create a hierarchy type for each product that your organization produces.

1.  Click **Human resources** \> **Setup** \> **Organization** \> **Position hierarchy types**.

2.  Click **New**.

3.  Enter a name for the hierarchy type.

4.  Repeat steps 2 and 3 for additional hierarchy types.

Back to top

 

## Set up compensation regions for positions

If you plan to use compensation regions in eligibility rules for compensation management, you should set up compensation regions before you create positions.

1.  Click **Human resources** \> **Setup** \> **Compensation** \> **Compensation regions**.

2.  Click **New**.

3.  Enter a name for the compensation region and a brief description of the region.

4.  Repeat steps 2 and 3 for additional compensation regions.

Back to top

 

## Set up personnel actions in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

If your organization uses personnel actions, complete the following setup tasks.


> [!NOTE]
> <P>For more information about personnel action types and why your organization might decide to use them, see <A href="about-departments-jobs-and-positions.md">About departments, jobs, and positions</A>.</P>



1.  Create personnel actions.
    
      - Click **Human resources** \> **Setup** \> **Actions** \> **Personnel action types**.
    
      - Click **New**.
    
      - Enter a name for the personnel action type and a brief description of the action.
    
      - Select an action from the list.
    
      - Repeat the previous steps to create additional personnel action types.
    
    This form is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the **Personnel actions** configuration key is selected.

2.  If your organization uses personnel actions, you can assign a number sequence to personnel actions.
    
      - Click **Human resources** \> **Setup** \> **Parameters** \> **Human resources shared parameters**.
    
      - Click **Number sequences**.
    
      - Select a number sequence code for the **Personnel action** reference.
    
    This option is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the **Personnel actions** configuration key is selected.

3.  If your organization uses personnel actions, you can create reason codes that users can select when they create and modify positions.
    
      - Click **Human resources** \> **Setup** \> **Parameters** \> **Reason codes**.
    
      - Click **New**.
    
      - Enter a reason code and description.
    
      - Select **Personnel action** from the **Type** column.
    
      - Repeat the previous steps to create additional reason codes.
    
    This option is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the **Personnel actions** configuration key is selected.

4.  If your organization uses workflow for one or more personnel action types, create Human resources actions workflows in the **Human resources workflows** form. (Click **Human resources** \> **Setup** \> **Human resource workflows**.)
    
    This option is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the **Personnel actions** configuration key is selected.

Back to top

 

## Create a new position


> [!NOTE]
> <P>The procedure for completing this task was changed for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  On the **Action Pane**, click **Position**.

3.  Enter a position ID.
    

    > [!NOTE]
    > <P>A default value might automatically be generated if a number sequence code is assigned to the <STRONG>Position</STRONG> reference in the <STRONG>Human resources shared parameters</STRONG> form.</P>



4.  Select the job that is associated with the position.
    
    The following information from the job that you select is copied to the new position:
    
      - Job description
    
      - Job title
    
      - Full-time equivalent employment factor

5.  Enter or accept the default activation date for the position.

6.  Optional: If known, enter the position retirement date. When the position is retired, if a worker is assigned to it, the assignment end date for the worker is changed to the retirement date.

7.  Click **Create positions**.

8.  You might have to click **Edit** on the **Action Pane** before you can complete one or more of the remaining steps in this procedure.
    

    > [!NOTE]
    > <P>The remaining steps in this procedure are optional.</P>



9.  Modify the description of the position. The default description is the description of the job that is associated with the position. Changing the position description does not change the description of the job.

10. Select a different job to associate with the position.

11. Select the department that the position belongs to.

12. Add reporting relationship information to the position. For more information, see the “Modify the reporting relationships for a position” section in the [Key tasks: Existing worker positions](key-tasks-existing-worker-positions.md) topic.

13. Accept the title that was copied from the job that is associated with the position, or select a different title for the position.

14. Select a position type for the position.

15. Accept the full time equivalent (FTE) employment factor that was copied from the job that is associated with the position, or enter a different FTE employment factor for the position.
    
    If you modify the FTE employment factor for the position, the FTE employment factor for the job that is associated with the position does not change.

16. Select a compensation region to associate with the position.

17. On the **Position duration** FastTab, enter the position duration.
    

    > [!TIP]
    > <P>If the retirement date is not known, select <STRONG>Never</STRONG>.</P>



18. On the **Worker assignment** FastTab, assign a different worker to the position, modify the existing worker assignment, or end the current worker assignment.

19. On the **Financial dimensions** FastTab, select a legal entity, and then select dimensions for that legal entity to allocate dimensions to the position. For more information, see [Create a financial dimension](create-a-financial-dimension.md).

Back to top

 

## Create a new position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.
    

    > [!NOTE]
    > <P>You can also create positions in the <STRONG>Position actions</STRONG> form.</P>



2.  On the **Action Pane**, click **Position**.
    
    If personnel actions are not enabled by your organization, enter the following:
    
      - **Position ID** – A default value might automatically be generated if a number sequence code is assigned to the **Position** reference in the **Human resources shared parameters** form.
    
      - **Job** – Select the job that is associated with the position. This job description, title, and full-time equivalent employment factor is automatically copied from the job.
    
      - **Activation** – Enter or accept the default activation date for the position.
    
      - **Retirement** – Optional: If known, enter the position retirement date. When the position is retired, if a worker is assigned to it, the assignment end date for the worker is changed to the retirement date.
    
    If personnel actions are enabled by your organization, enter the following:
    
      - **Personnel action number** – The unique identifier that is assigned to the action. If your organization has not set up personnel action number sequences, enter this number.
    
      - **Personnel action type** – The values for this field are entered in the **Personnel action types** form. Action types of **Create positions** are displayed. For more information, see [Configure personnel actions](configure-personnel-actions.md).
    
      - **Reason code** – The reason that you are completing the action.

3.  Click **Create positions** or **Continue**.

4.  Enter the description of the position.

5.  Select a job to associate with the position.

6.  Select the department that the position belongs to.

7.  Add reporting relationship information to the position. For more information, see the “Modify the reporting relationships for a position” section in [Key tasks: Existing worker positions](key-tasks-existing-worker-positions.md) topic.

8.  Accept the title that was copied from the job that is associated with the position, or select a different title for the position.

9.  Select a position type for the position.

10. Accept the full time equivalent (FTE) employment factor that was copied from the job that is associated with the position, or enter a different FTE employment factor for the position.
    
    If you modify the FTE employment factor for the position, the FTE employment factor for the job that is associated with the position does not change.

11. Select a compensation region to associate with the position.

12. In the **Available for assignment**, field, enter the date when workers can be assigned to the position. To prevent workers from being assigned to the position, enter a future date in this field. To allow for worker assignments immediately, enter the current date.

13. On the **Position duration** FastTab, enter the position duration.
    

    > [!TIP]
    > <P>If the retirement date is not known, select <STRONG>Never</STRONG>.</P>



14. On the **Payroll** FastTab, assign a pay cycle, select the legal entity that pays the position, and enter any information that is required to calculate earnings.
    

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Payroll - USA</STRONG> configuration key is selected.</P>



15. On the **Financial dimensions** FastTab, select a legal entity, and then select dimensions for that legal entity to allocate dimensions to the position. For more information, see [Create a financial dimension](create-a-financial-dimension.md).

16. Click **Complete** or **Continue**.
    

    > [!NOTE]
    > <P>If your organization uses workflow, you have to submit the position for review before it is completed.</P>



Back to top

 

## Create one or more new positions from an existing position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3

Use the **Positions** list page to create new positions by copying an existing position that has similar characteristics.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  Select the position to copy.

3.  On the **Action Pane**, in the **New** group, click **Copy position**.

4.  Enter the number of new positions to create in addition to the one that already exists.

5.  Enter the position duration to assign to each new position.

6.  Select the position detail tabs to copy:
    
      - **Relationships** – Copy the hierarchy name and the person the positions will report to from the selected position.
    
      - **Financial dimensions** – Copy the legal entity, default financial dimensions, and budget defaults from the selected position.
    
      - **Payroll** – Copy all payroll and workers’ compensation information from the selected position.
    
      - **Labor union** – Copy the labor union agreement and details from the selected position.

7.  Click **Copy**. Each of the new positions will appear in the **Positions** list page.
    

    > [!NOTE]
    > <P>When you copy an existing position, the <STRONG>Available for assignment</STRONG> field is not copied, but is set to the default value on the <STRONG>Positions</STRONG> tab in the <STRONG>Human resources shared parameters</STRONG> form.</P>



Back to top

 

## Create one or more new positions from an existing position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3 when personnel actions are enabled

Create one or more new positions by copying an existing position that has similar characteristics.

1.  Click **Human resources** \> **Common** \> **Organization** \> **Positions** \> **Positions**.

2.  On the **Action Pane**, click **Position**.
    
    Enter the following:
    
      - **Personnel action number** – The unique identifier that is assigned to the action. If your organization has not set up personnel action number sequences, enter this number.
    
      - **Personnel action type** – The values for this field are entered in the **Personnel action types** form. Action types of **Create positions** are displayed. For more information, see [Configure personnel actions](configure-personnel-actions.md).
    
      - **Reason code** – The reason for the action.

3.  Click **Continue**.

4.  On the **Action Pane**, in the **Maintain** group, click **Copy values from position**.

5.  Select the position to copy.

6.  Click **Copy values**.

7.  In the **Position action** form, enter the number of new positions to create. After you complete the action, the same number of new positions is available in the **Position** form and has the same field values that you enter in this **Position action** form.

8.  Make any changes to the position.

9.  Click **Complete**. A confirmation message appears that states the number of new positions that were created, and the new positions will appear on the **Newly created positions** tab. Click any new position to open the **Positions** form.
    
    If you received any errors, no new positions were created, and you can either reactivate or delete the position action. If there were no errors, the position action is available on the **Position actions** list page for historical reference.
    

    > [!NOTE]
    > <P>If your organization uses workflow, you have to submit the position for review before it is completed.</P>



Back to top

## Find form help

[Position hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh242466\(v=ax.60\))

[Position type (form)](https://technet.microsoft.com/en-us/library/hh209577\(v=ax.60\))

[Positions (form)](https://technet.microsoft.com/en-us/library/aa590982\(v=ax.60\))

## Find related tasks

[Key tasks: Departments](key-tasks-departments.md)

[Key tasks: Jobs](key-tasks-jobs.md)

  


