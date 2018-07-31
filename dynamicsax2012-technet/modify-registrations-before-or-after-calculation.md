---
title: Modify registrations before or after calculation
TOCTitle: Modify registrations before or after calculation
ms:assetid: fdf60b94-ce2d-44ba-a43e-cfa27e86d127
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa573440(v=AX.60)
ms:contentKeyID: 43976733
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- absence
- clock-out
- missing
- calculate
- edit
audience: Application User
ms.search.region: Global
---

# Modify registrations before or after calculation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can modify registrations made by workers before or after you calculate the registrations.

After you calculate or approve registrations, you can view error descriptions on the **Error** tab in the **Calculate** form and the **Approve** form. For example, an error message may inform you that information about a worker’s absence time is missing.

## Update an absence registration

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**. In the **Calculate** dialog box, in the **Date** and **Calculation group** fields, enter the date and calculation group to calculate registrations for. Click **OK**.

2.  In the **Calculate** form, select the worker in the upper pane, and then, on the **Absence** tab, modify the absence registration that was entered during calculation. You can also press CTRL+N to create a new absence registration.

3.  Press CTRL+S to save absence records. The absence records are displayed in the lower pane on the **Overview** tab.

4.  Follow steps 1 through 3 for every worker for whom an absence registration is required.


> [!NOTE]
> <P>When you calculate registrations for a group of workers, any missing absence records for the workers are created automatically. For those absence records, you only have to select the absence codes. Start times and end times are added automatically during calculation.</P>



## Approve switch codes for a worker

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**. In the **Calculate** dialog box, in the **Date** and **Calculation group** fields, enter the date and calculation group to approve switch codes for. Click **OK**.

2.  In the **Calculate** form, select the worker in the upper pane, and then click **Switch code**.

3.  Select the **Approved** check box, and close the form.

## Add a missing clock-out registration

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**. In the **Calculate** dialog box, in the **Date** and **Calculation group** fields, enter the date and calculation group to add clock-out registrations for. Click **OK**.

2.  In the **Calculate** form, select the worker in the upper pane, and then click **Clock-in and out** \> **Missing clock-out**.

3.  In the **Clock out** section, select the date and time for the clock-out registration.

4.  Select the **Create lines** check box, and then click **OK**.

## Clock out all workers in a calculation group

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**. In the **Calculate** dialog box, in the **Date** and **Calculation group** fields, enter the date and calculation group to calculate registrations for. Click **OK**.

2.  In the **Calculate** form, click **Clock-in and out** \> **Clock out workers**.

3.  In the **Profile date** field, select the clock-out date, and then click **OK**.


> [!NOTE]
> <P>All workers in the selected calculation group are clocked out according to their work time profile. For more information, see <A href="about-profiles-for-time-and-attendance-registrations.md">About profiles for time and attendance registrations</A>.</P>
> <P>Also, you can create a batch job that clocks out all workers in a calculation group. For more information, see <A href="submit-a-batch-processing-job-from-a-form.md">Submit a batch processing job from a form</A>.</P>



## Correct errors and add registrations

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**. In the **Calculate** dialog box, in the **Date** and **Calculation group** fields, enter the date and calculation group to calculate registrations for. Click **OK**.

2.  In the **Calculate** form, select the worker in the upper pane. In lower pane, click the registration to modify, or press CTRL+N to add a new line.

3.  Enter information for the registration line.

4.  To recalculate the worker’s registrations, in the upper pane, on the **Overview** tab, select the **Calculated** check box.


> [!IMPORTANT]
> <P>Do not create a new journal line for a clock-out registration if a worker did not clock out. To create missing clock-out registrations, click <STRONG>Clock-in and out</STRONG>, and then select the appropriate option. Only these two options make sure that the clock-out registration is entered in the <STRONG>Raw registrations</STRONG> table. Raw registrations determine whether the worker is clocked in or clocked out.</P>



## See also

[About calculating, approving and transferring registrations](about-calculating-approving-and-transferring-registrations.md)

[Calculate time and attendance for workers](calculate-time-and-attendance-for-workers.md)

[Approve time and attendance registrations](approve-time-and-attendance-registrations.md)

  


