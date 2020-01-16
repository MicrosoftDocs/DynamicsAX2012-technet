---
title: Transfer time and attendance registrations
TOCTitle: Transfer time and attendance registrations
ms:assetid: 06eb0bfb-b85b-49bf-8be9-b6f2330faf64
ms:mtpsurl: https://technet.microsoft.com/library/Aa569720(v=AX.60)
ms:contentKeyID: 39519039
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reversal
- transfer
audience: Application User
ms.search.region: Global
---

# Transfer time and attendance registrations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Registrations must be transferred to journals, such as production or project journals.

After workers’ registrations are approved, and no errors occur, you can transfer the registrations. You can transfer registrations in one of the following ways:

  - Transfer registrations by using a workflow.

  - Transfer registrations by using a batch job.

  - Transfer registrations manually for an approval group.

  - Transfer registrations manually for one worker at a time.

## Transfer registrations using a workflow

If an approval workflow is set up to approve registrations based on a set of predefined rules, the system transfers all approved registrations to the appropriate journals. Only deviations that are not accepted in the workflow are handled manually. This means that approval and transferal of those registrations is performed by the worker responsible for approving registrations, for example, a payroll administrator. For more information, see [Approve time and attendance registrations](approve-time-and-attendance-registrations.md).

## Transfer registrations using a batch job

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Approve**.

2.  Select the approval date in the **Date** field.

3.  Select your group in the **Approval group** field.

4.  Click **Update** and then **Transfer**.

5.  Start the batch job. For more information, see [Transfer registrations (class form)](https://technet.microsoft.com/library/aa548840\(v=ax.60\)).

## Transfer registrations for all workers in an approval group

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Approve**.

2.  Select the approval date in the **Date** field.

3.  Select your group in the **Approval group** field.

4.  Click **Update** and **Transfer**.

5.  Click **OK**.


> [!NOTE]
> <P>You can only transfer registrations that have been calculated and approved without errors.</P>




> [!TIP]
> <P>To view a list of worker registrations that contain errors in the registration lines, click <STRONG>Display errors</STRONG>. The <STRONG>Error</STRONG> tab provides information about the type of error.</P>



## Transfer registrations for one worker

When an error is found in a worker registration, you can transfer the registration after you have corrected the error.

1.  In the **Approve** form, select the worker in the upper pane.

2.  Select the **Transferred** check box for the worker.

## Reverse a transferred registration

You can reverse transferred registrations for a worker before payroll information for the period is exported to the payroll system. Do the following to reverse transferred registrations for a worker:

1.  In the **Approve** form, select the worker in the upper pane.

2.  Clear the **Transferred** check box.

## See also

[About calculating, approving and transferring registrations](about-calculating-approving-and-transferring-registrations.md)

[Approve time and attendance registrations](approve-time-and-attendance-registrations.md)

  


