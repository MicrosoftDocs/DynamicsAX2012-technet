---
title: Create policies
TOCTitle: Create policies
ms:assetid: 408f928e-aab0-4ad7-bf3f-1f5c1fc0a590
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231354(v=AX.60)
ms:contentKeyID: 36056719
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create policies [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create policies that employees must follow when they submit expense reports. For example, you can create a policy that expense reports must include original receipts for any transactions with recoverable Value Added Tax (VAT). Or, you can create a policy that original receipts must be submitted for all transactions with an amount larger than 100.00 EUR.

When these policies are active, if an employee submits an expense report that violates a policy, the employee automatically receives a message. The message explains which policy has been violated and what action to take. Depending on how you set up your policies, the employee might still be able to submit the report. If so, the problematic transactions are marked for the expense report approver to review. If the policy states that the report cannot be submitted, the employee must change the transactions that violate the policies and resubmit the report.

1.  Click **Travel and expense** \> **Setup** \> **Policies** \> **Expense report**.

2.  Click the **Policy** button in the **New** group to create a new policy.

3.  Enter a name and a description for the new policy.

4.  On the **Policy organizations** tab, select the organizations that you want the policy to apply to.

5.  On the **Policy rules** tab, click **Create policy rule**.

6.  In the **Expense** form, in the **Effective date** and **Expiration date** fields, enter dates to set the period for which the policy will be active. If no end date is specified, the policy will remain active indefinitely.

7.  Click **Add condition**, and then select a field name, operator, and value for the policy.
    
    For example:
    
      - Where –**Amount**\>= to 100.00 EUR
    
      - And – Expense line.Receipts attached is Yes.

8.  Repeat step 7 to add more conditions.

9.  In the **Do the following** field, select the actions that are enabled when the policy is violated.

10. Enter the message that the employee receives if the policy is violated. You can create this message in multiple languages, as needed.

## See also

[About travel and expense policies](about-travel-and-expense-policies.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

