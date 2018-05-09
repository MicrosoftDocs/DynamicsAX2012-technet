---
title: Set up signing limit parameters
TOCTitle: Set up signing limit parameters
ms:assetid: a885800b-5282-4e5b-bb64-9078347de802
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242689(v=AX.60)
ms:contentKeyID: 36058887
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up signing limit parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Signing limit parameters are the basis for the signing limit policy configuration steps. On the parameters form, you define whether signing limits are enforced, based on job or compensation level, you define signing limit revocation reasons, and you define limit agreements.

## Define the signing-limit basis

Signing limits are based on either the employee’s job or compensation level.


> [!NOTE]
> <P>Jobs are defined in Microsoft Dynamics AX on the <A href="https://technet.microsoft.com/en-us/library/hh209557(v=ax.60)">Job (form)</A> or are based on compensation level defined in the <A href="https://technet.microsoft.com/en-us/library/hh803022(v=ax.60)">Compensation structure (form)</A>.</P>



1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit parameters**.

2.  Select **Job** if signing limits should be based on your employees’ job. Select **Compensation level** if signing limits should be based on your employees’ compensation level.

3.  Select the **Require explicit signing limit request** check box to force employees to submit a signing limit request in order to be granted a spending or approval limit. If this box is not selected, employees will be granted the default spending or approval limit as defined for their job or compensation level.

4.  Select the **Signing limits for employees only** check box if employees should be allowed to request and be granted signing limits. If this check box is not selected, contract employees will also be permitted to submit and be granted signing limits.

## Define signing limit revocation reasons

There are times when signing limits are revoked. For example, if an employee is found to be abusing their spending privilege or if an employee tenders their resignation, their signing limit should be revoked. Predefined revocation reasons help ensure a clean signing limit revocation process and standardize the process for future tracking and reporting purposes. Revocation reason codes can be used later by managers to revoke an employee’s signing limit using the employee portal on Enterprise Portal for Microsoft Dynamics AX.

1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit parameters**. Click the **Revocation reasons** FastTab.

2.  Click **Add**.

3.  Enter a **Reason code**.

4.  Enter a reason code description.

## Define limit agreements

Limit agreements are agreements that employees are required to read and accept in order to be granted a signing limit authorization. On the **Signing limit parameters** form, you can define all limit agreements and their URL locations. Then, as a part of defining a signing limit policy, define the signing limit agreements associated with the policy. These are the specific limit agreements required for the policy being created.

1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit parameters**. Click the **Agreements** FastTab.

2.  Click **Add**.

3.  Enter a **Name** for the limit agreement.

4.  Enter the **URL** for the signing limit agreement.

5.  In the **Duration of agreement (in months)** field, specify the number of months that the employee’s confirmation of the terms of the limit agreement are valid.

## See also

[Signing limit parameters (form)](https://technet.microsoft.com/en-us/library/hh209378\(v=ax.60\))

[About signing limit setup](about-signing-limit-setup.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

