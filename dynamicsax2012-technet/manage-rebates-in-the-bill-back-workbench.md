---
title: Manage rebates in the bill back workbench
TOCTitle: Manage rebates in the bill back workbench
ms:assetid: 16a4407d-b566-4587-bfc6-3d6cdba13900
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497717(v=AX.60)
ms:contentKeyID: 62490076
ms.date: 06/10/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TAMBillBackListPage
---

# Manage rebates in the bill back workbench [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to process customer rebate payments from the bill back workbench in **Trade allowance management**. A rebate is a partial refund of a payment that a customer previously paid for an item or service. Rebates are usually given as part of a promotion or marketing activity. A customer can use a rebate as a deduction on an outstanding balance or take the amount of the rebate as a credit. (For more information about rebates with deductions, see [Manage deductions in the deduction workbench](manage-deductions-in-the-deduction-workbench.md).) If the customer does not use the rebate as a deduction, a credit note is issued in the bill back workbench when the customer’s transaction is complete. Rebates are configured so that the appropriate department and promotional category in your organization is billed for the credit that is returned to the customer.

## Prerequisite

Before you can create a credit note for a rebate and use the bill back workbench, you must have some type of trade allowance rebate agreement set up for the customer. For more information about trade allowance rebates, see [Set up rebates](set-up-rebates.md).

## Create a credit note for a customer

After you invoice a sales order for a customer, you can create a credit note on the customer's account to represent a rebate. The credit then appears in the bill back workbench, where it can be matched to a rebate.

To create a credit note, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Customers** \> **All customers**.

2.  Select the customer, and then, on the **Action Pane**, on the **Collect** tab, in the **Settle** group, click **Settle open transactions**.

3.  Select the transaction that the rebate was applied to. On the **Action Pane**, click **Functions**, and then select the type of rebate program that applies.

4.  On the **Overview** tab, select the **Mark** check box next to the rebate ID. Click **Functions**, and then click **Create credit note**.

## Process and approve rebates in the bill back workbench

In the bill back workbench, you can accumulate, approve, and process rebates. Depending on how you want to process the rebate, complete one of the following procedures.

To process one rebate for a customer, follow these steps:

1.  Click **Trade allowance management** \> **Common** \> **Bill back workbench**.

2.  Select the **Mark** check box next to the rebate that you want to process, and then, on the **Action Pane**, click **Approve**.

To collect and process multiple rebates for a customer, follow these steps:

1.  Click **Trade allowance management** \> **Common** \> **Bill back workbench**.

2.  On the **Action Pane**, in the **Functions** group, click **Cumulate**.

3.  In the **Cumulate rebates** form, select the customer ID, the start date, and the end date of the rebate period, and then click **OK**.
    
    The rebates for the selected customer are shown on the **Bill back workbench** list page.

4.  Select the rebates that you want to approve, and on the **Action Pane**, in the **Functions** group, click **Approve**.

## Process approved rebates

After you approve the rebates, they must be processed for posting. To process approved rebates, follow these steps:

1.  Click **Trade allowance management** \> **Common** \> **Bill back workbench**.

2.  On the **Action Pane**, in the **Functions** group, click **Process**.

3.  In the **Process rebates** form, select the customer account, customer rebate group, or trade management allowance group on which to filter the rebates for processing, and then click **OK**.

After you click **OK**, the invoice is posted and the status of the rebate claim is set to completed.

## Delete outdated rebates

At some point, you will need to remove outdated rebate information from Microsoft Dynamics AX. To delete outdated rebate records, follow these steps:

1.  Click **Trade allowance management** \> **Common** \> **Bill back workbench**.

2.  On the **Action Pane**, in the **Functions** group, click **Purge**.

3.  In the **Rebate purge** form, enter the earliest date for the rebates that you want to keep. For example, if you enter May 1, 2014, all rebates that were created before May 1, 2014 will be deleted.

4.  Click **OK**.

## See also

[Manage deductions in the deduction workbench](manage-deductions-in-the-deduction-workbench.md)

[Set up trade allowance funds](set-up-trade-allowance-funds.md)

[Set up rebates](set-up-rebates.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

