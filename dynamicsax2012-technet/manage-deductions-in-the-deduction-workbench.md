---
title: Manage deductions in the deduction workbench
TOCTitle: Manage deductions in the deduction workbench
ms:assetid: ef11d6e5-7dfc-4af8-bc71-1dffc538a47e
ms:mtpsurl: https://technet.microsoft.com/library/Dn497849(v=AX.60)
ms:contentKeyID: 62200182
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- deduction
- deductions
- Forms.TAMDeduction
- Forms.TAMDeductionType
- Forms.TAMDeductionWriteOffReason
- Forms.TAMDeductionDenyReason
- MsDynAx060.Forms.TAMDeduction
- Forms.TAMDeductionCreate
- Forms.TAMDeductionParmDeny
- Forms.TAMDeductionParmMatch
- Forms.TAMDeductionParmSplit
- Forms.TAMDeductionParmMassUpdate
- Forms.TAMDeductionParmWriteOff
- MsDynAx060.Forms.TAMDeductionParmSplit
- MsDynAx060.Forms.TAMDeductionParmMatch
- MsDynAx060.Forms.TAMDeductionParmDeny
- MsDynAx060.Forms.TAMDeductionParmWriteOff
- Forms.TAMOneTimePromotion
- MsDynAx060.Forms.TAMDeductionParmMassUpdate
- MsDynAx060.Forms.TAMDeductionCreate
- MsDynAx060.Forms.TAMOneTimePromotion
- rebates
- deduction workbench
- payment deduction
- trade allowance rebates
audience: Application User
ms.search.region: Global
---

# Manage deductions in the deduction workbench 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to use the deduction workbench to process customer payments that include deductions.

A customer who is owed a rebate can decide not to wait for a rebate payout. Instead, the customer can send a payment that includes a deduction for the amount of the rebate. To handle this type of transaction, you can use the deduction workbench to match deductions to open credit transactions, split deductions, deny deductions, and write off deductions.

Before you can use the workbench, you must complete the setup tasks that are described in [Set up deduction management](set-up-deduction-management.md). You should also have some type of rebate agreement set up for the customer: either a customer rebate, as described in [Setting up and maintaining customer rebates](setting-up-and-maintaining-customer-rebates.md), or a trade allowance rebate, as described in Set up billback rebates.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required setup and processing tasks</p></td>
<td><p><a href="set-up-deduction-management.md">Set up deduction management</a></p>
<p>If you are applying a deduction to a customer rebate:</p>
<ul>
<li><p><a href="setting-up-and-maintaining-customer-rebates.md">Setting up and maintaining customer rebates</a></p></li>
<li><p>Note that you must also approve and process the rebate before you can use the deduction workbench.</p></li>
</ul>
<p>If you are applying a deduction to a trade allowance rebate:</p>
<ul>
<li><p>Set up billback rebates</p></li>
<li><p>Apply billback rebates</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Create a deduction journal entry

Enter the deduction information into the payment journal.

To create a deduction journal entry, follow these steps.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **New**, and then, in the **Name** field, select the name of the deduction journal.

3.  On the **Action Pane**, click **Lines**.

4.  Enter the date, company account, and customer account number. In the **Invoice** field, select the invoice that the deduction is associated with.

5.  In the **Credit** field, enter the amount that the customer paid. Click **OK** to confirm that the amount is less than the total of the marked transaction.

6.  Select the offset account type and the offset account.

7.  On the **Action Pane**, click **\>\>**, and then click **Deductions**. In the **Deduction** form, click **New**.

8.  The **Deduction ID** field is populated automatically. Select the deduction type in the list.

9.  In the **Amount** field, enter the amount that is displayed in the **Balance** field above the deduction list. This amount represents the amount that the customer deducted from the payment.

10. Close the **Deduction** form. In the **Journal voucher** form, a new line is displayed for the deduction.

11. On the **Action Pane**, click **Validate**, and then select **Validate**. You should receive the following message: "Journal is OK."

12. On the **Action Pane**, click **Post**, and then select **Post**.

## 2\. (If required) Create a credit note for the customer

Next, if an approved rebate exists for the customer, create a credit note on the customer's account to represent the rebate. The credit then appears in the deduction workbench, where it can be matched to a deduction.

To create a credit note, follow these steps.

1.  Click **Sales and marketing** \> **Common** \> **Customers** \> **All customers**.

2.  Select the customer, and then, on the **Collect** tab, in the **Settle** group, click **Settle open transactions**.

3.  Select the transaction that the rebate was applied to. On the **Action Pane**, click **Functions**, and then select the type of rebate program that applies.

4.  On the **Overview** tab, select the **Mark** check box next to the rebate ID. Click **Functions**, and then click **Create credit note**.

## 3\. Process a deduction in the deduction workbench

In the deduction workbench, you can match deductions to open credit transactions, split deductions, deny deductions, and write off deductions.

To process a deduction in the deduction workbench, follow these steps.

1.  Click **Trade allowance management** \> **Common** \> **Deduction workbench**.

2.  Select the **Mark** check box next to the deduction to process.

3.  Depending on how you want to process the deduction, complete one or more of the following procedures:
    
      - To match the deduction to a credit:
        
        1.  In the **Open transactions** area, select the **Mark** check box for the credit to match to the deduction. If multiple credits are listed, you can select more than one credit to match to the deduction.
            
            –or–
            
            If you want the system to automatically select credits that match the amount of the deduction, click **Select deduction amount**.
        
        2.  On the **Action Pane**, in the **Maintain** group, click **Match**. The system matches the deduction to the credit. If a balance remains in the deduction, this balance appears in the **Remaining amount** field on the **Deductions** tab.
    
      - To split the deduction:
        
        1.  On the **Action Pane**, in the **Maintain** group, click **Split**.
        
        2.  In the **Split amount** field, enter the amount to split from the main deduction. Click **OK** at the top of the **Split** form and then close the form.
        
        3.  On the **Deductions** tab, notice that a new record appears for the split amount. The original deduction record contains the remainder of the deduction balance. You can now manage the two parts of the original rebate separately.
        
        4.  Select the original deduction record, and then click the **References** tab. The **Split amount** field shows the amount that was split off from the original amount.
    
      - To deny the deduction:
        
        1.  On the **Action Pane**, in the **Maintain** group, click **Deny**.
        
        2.  Select the reason code for the denial. Click **OK** at the top of the **Deny** form and then close the form.
        
        3.  In the **Show** field below the **Action Pane**, select **Closed**. The denied deduction is displayed on the **Deductions** tab, and the remaining amount for the deduction is set to **0.00**.
        
        4.  Optional: To reverse the denial, select the deduction record, and then, on the **Action Pane**, in the **Reverse** group, click **Reverse denial**.
    
      - To write off the deduction:
        
        1.  On the **Action Pane**, in the **Maintain** group, click **Write-off**.
        
        2.  Select the reason code for the write-off. Click **OK** at the top of the **Write-off** form and then close the form.
        
        3.  In the **Show** field, select **Closed**. The written-off deduction is displayed on the **Deductions** tab, and the remaining amount for the deduction is set to **0.00**.
        
        4.  Optional: To reverse the write-off, select the deduction record, and then, on the **Action Pane**, in the **Reverse** group, click **Reverse write-off**.
    
    You can combine these procedures. For example, you can split a deduction into two parts, and then match one part to a credit but leave the remaining part in the workbench to be matched to another credit later. You can also can match a deduction to a credit that is smaller than the deduction amount, and then deny or write off the remaining balance of the deduction.

## 4\. Optional: Create an end-of-period promotion

Sometimes, you might not have an approved rebate that you can match to a deduction. In this case, you can use the **End of period promotion** feature to match the deduction to a trade allowance that is associated with the customer. The **End of period promotion** feature creates a new trade allowance agreement and a lump sum merchandising event. The feature then matches the lump sum to the deduction and makes the postings that are required to close the deduction.

This feature is useful if you use trade allowances. For more information about trade allowances, see [Working with Trade allowance management](working-with-trade-allowance-management.md).

First, you must set up a template to use to create the new trade allowance agreement. To set up a template, follow these steps.

1.  Click **Trade allowance management** \> **Periodic** \> **Templates**.

2.  On the **Action Pane**, in the **New** group, click **Templates**.

3.  Fill in the fields with the information that should appear in the agreements that are created from the template. For more information about the fields in a trade allowance agreement, see Set up a trade allowance template.

4.  On the **Customers** FastTab, in the **Hierarchy** field, select a hierarchy level. In the hierarchy list, select the customer who has an unmatched deduction, and then click **\>**. The customer is added to the **Trade allowance agreement customers** list.

5.  Continue to fill in the remaining fields as you require, and then close the form.

6.  Click **Trade allowance management** \> **Setup** \> **Trade allowance management parameters**.

7.  On the **General** FastTab, in the **End of period template** field, select the name of the template to use to create end-of-period promotions.

Next, you can create an end-of-period promotion in the deduction workbench. To create an end-of-period promotion, follow these steps.

1.  Click **Trade allowance management** \> **Common** \> **Deduction workbench**.

2.  Select the **Mark** check box next to the deduction to process.

3.  On the **Action Pane**, in the **Maintain** group, click **End of period promotion**.

4.  Optional: If you want to associate the deduction with one or more funds, follow these steps:
    
    1.  Click **New**, and then, in the **Fund ID** field, select a fund ID. Repeat this step to add as many funds as you require.
    
    2.  In the **Percent** field next to each fund ID, enter the percentage of the deduction to allocate to the fund. The amounts that you enter in the **Percent** fields must total 100 percent.

5.  On the **Action Pane**, click **OK**. The system creates a new trade allowance agreement that has a lump sum merchandising event and matches the lump sum to the deduction.

## 5\. Optional: Perform a mass update of deductions

If you have to make the same change to multiple deductions, you can select those deductions and perform a mass update of their fields.

To perform a mass update, follow these steps.

1.  Click **Trade allowance management** \> **Common** \> **Deduction workbench**.

2.  In the **Show** field below the **Action Pane**, select the type of deductions to view (**Created**, **Open**, or **Closed**).

3.  Select the **Mark** check box next to each deduction to update. On the **Action Pane**, in the **Maintain** group, click **Mass update**.

4.  The selected deductions are listed in the **Mass update** form. Update the fields as you require, and then click **OK** at the top of the form to accept the changes.

## Related tasks

[Set up deduction management](set-up-deduction-management.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Trade allowance management</strong> configuration key</p>
<p><strong>Rebates</strong> configuration key (if you are using customer rebates)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Collections manager</p></td>
</tr>
</tbody>
</table>


## See also

[Setting up and maintaining customer rebates](setting-up-and-maintaining-customer-rebates.md)

  


