---
title: Approve time and attendance registrations
TOCTitle: Approve time and attendance registrations
ms:assetid: 09c79081-edec-4e3a-a7ee-eb0d5c239467
ms:mtpsurl: https://technet.microsoft.com/library/Aa569735(v=AX.60)
ms:contentKeyID: 49384093
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reversal
- approve
audience: Application User
ms.search.region: Global
---

# Approve time and attendance registrations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After each work day, workers’ registrations must be calculated and approved. You can approve registrations after they have been calculated, and no errors occurred during calculation. You can approve registrations by using one of the following:

  - A workflow

  - A batch job

  - Manually for an approval group

  - Manually for one worker at a time

## Approve registrations using a workflow

The approval workflow is an automatic approval process. All registrations are validated against the rules in the approval workflow. Only deviations that are not accepted in the workflow must be approved manually. For more information, see [About calculating, approving and transferring registrations](about-calculating-approving-and-transferring-registrations.md) The worker who is responsible for calculating registrations, for example, a team leader, initiates the approval process. The worker who is responsible for approving registrations, for example, a payroll administrator, receives a message regarding the need for manual approval only when some registrations could not be approved according to the approval workflow.

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Approve**.

2.  Select the approval date in the **Date** field.

3.  Select your group in the **Approval group** field.

4.  In the **Approve** form, select the worker in the upper pane, on the **Overview** tab.

5.  Click the **Action** button. If the worker’s registrations are ready for approval, the **Approve** and **Reject** options are available.
    
      - To approve, click **Approve**.
    
      - To reject, click **Reject**, and insert a note explaining why the registrations are rejected.

## Approve registrations using a batch job

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Approve**.

2.  Select the approval date in the **Date** field.

3.  Select your group in the **Approval group** field.

4.  Click **Update** and **Approve**.

5.  Start the batch job. See [Approve registrations (class form)](https://technet.microsoft.com/library/aa551722\(v=ax.60\)) regarding how to create a batch job.

## Approve registrations for all workers in an approval group

1.  Click **Human resources** \> **Common** \> **Time and attendance** \> **Approve**.

2.  Select the approval date in the **Date** field.

3.  Select your group in the **Approval group** field.

4.  Click **Update** and **Approve**.

5.  Click **OK**.


> [!NOTE]
> <P>If the approval process returns errors on some registrations, for example because of missing information, you must edit those registrations and approve again.</P>




> [!TIP]
> <P>To see a list of worker registrations that contain errors in the registration lines, click <STRONG>Display errors</STRONG>. The <STRONG>Error</STRONG> tab provides information about the type of error.</P>



## Approve registrations for one worker at a time

You typically must approve registrations for an individual worker after you have corrected errors for that worker.

1.  In the **Approve** form, select the worker in the upper pane.

2.  Select the **Approved** check box for the worker.

## Reverse an approval

Approved registrations for a worker can be reversed until payroll information for the period has been exported to the payroll system. Do the following to reverse approved registrations for a worker:

1.  In the **Approve** form, select the worker in the upper pane.

2.  Clear the **Approved** check box.


> [!TIP]
> <P>If you have made several corrections to the registrations, and, therefore, must restore the lines to their original value, delete all lines, and then click <STRONG>Restore lines</STRONG>.</P>



## See also

[About calculating, approving and transferring registrations](about-calculating-approving-and-transferring-registrations.md)

[Modify registrations before or after approval](modify-registrations-before-or-after-approval.md)

[Calculate time and attendance for workers](calculate-time-and-attendance-for-workers.md)

[Transfer time and attendance registrations](transfer-time-and-attendance-registrations.md)

  


