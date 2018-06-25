---
title: Calculate time and attendance for workers
TOCTitle: Calculate time and attendance for workers
ms:assetid: eb4d224c-e5b9-476d-b10e-d2f1bba488b5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551501(v=AX.60)
ms:contentKeyID: 43976731
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- absence
- calculate
---

# Calculate time and attendance for workers [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can calculate time and attendance registrations for workers in the following ways:

  - Calculate registrations for all workers who are assigned to a calculation group.

  - Calculate registrations for a specific worker.

  - Calculate registrations by using a batch job.

You can use the **Day view** and **Week view** filters as follows:

  - **Day view** – View registrations for all workers for a selected weekday.

  - **Week view** – View registrations for a selected worker for a selected week.

## Calculate registrations for all workers in a calculation group

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**.

2.  In the **Week** or **Date** field, select the week or date to calculate registrations for.

3.  In the **Calculation group** field, select the calculation group to calculate registrations for, and then click **OK**.

4.  In the **Calculate** form, click **Update** \> **Calculate**.

5.  In the **Calculates jobs** form, verify that the calculation group is selected in the **Calculation group** field.

6.  If you use a workflow for approvals, select the **Submit to workflow** check box in the **Calculates jobs** form.

7.  Click **Close**.


> [!NOTE]
> <P>If registrations contain errors because of missing information or for other reasons, you must correct the registrations, and then calculate the registrations again. To view the worker registrations that contain errors, click <STRONG>Display errors</STRONG>. The <STRONG>Error</STRONG> tab displays information about the type of error.</P>



## Calculate registrations for one worker at a time

You can calculate registrations for a specific worker. Typically, you calculate registrations for a worker after you have corrected registration errors for that worker.

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**.

2.  In the **Week** or **Date** field, select the week or date to calculate registrations for.

3.  In the **Calculation group** field, select the calculation group to calculate registrations for, and then click **OK**.

4.  In the **Calculate** form, select the worker in the upper pane and click **Select**.

5.  Select the **Calculated** check box for the registration.

6.  Click **Close**.

## Reverse calculated registrations

You can reverse the registrations that have been calculated for a worker. However, you cannot reverse calculated registrations after payroll information for the period has been exported to the payroll system. Also, if registrations have been approved, you can reverse the calculated registration only in the **Approve** form.

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**.

2.  In the **Week** or **Date** field, select the week or date to calculate registrations for.

3.  In the **Calculation group** field, select the calculation group to calculate registrations for, and then click **OK**.

4.  In the **Calculate** form, select the worker in the upper pane and click **Select**.

5.  Clear the **Calculated** check box for the registration.

6.  Click **Close**.


> [!TIP]
> <P>If you have changed the registrations, and you want to restore the original values, delete all lines, and then click <STRONG>Restore lines</STRONG>.</P>



## Calculate registrations by using a batch job

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Calculate**.

2.  In the **Week** or **Date** field, select the week or date to calculate registrations for.

3.  In the **Calculation group** field, select the calculation group to calculate registrations for, and then click **OK**.

4.  In the **Calculate** form, click **Update**, and then click **Calculate**.

5.  In the **Calculates jobs** form, click the **Batch** tab.

6.  Start the batch job. For more information, see [Calculates jobs (class form)](https://technet.microsoft.com/en-us/library/aa573289\(v=ax.60\)).
    

    > [!NOTE]
    > <P>If you use a workflow for approvals, select the <STRONG>Submit to workflow</STRONG> check box.</P>



7.  Click **OK**.

## See also

[About calculating, approving and transferring registrations](about-calculating-approving-and-transferring-registrations.md)

[Modify registrations before or after calculation](modify-registrations-before-or-after-calculation.md)

[Approve time and attendance registrations](approve-time-and-attendance-registrations.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

