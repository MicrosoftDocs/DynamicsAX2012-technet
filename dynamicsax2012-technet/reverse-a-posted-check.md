---
title: Reverse a posted check
TOCTitle: Reverse a posted check
ms:assetid: e3727e47-80cf-493a-add4-4c5d8e912ea6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243217(v=AX.60)
ms:contentKeyID: 36059722
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- reversal
- check
- checks
- check reversal
- check reversals
- reversals
---

# Reverse a posted check 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to reverse a check and how to review the reversal.

There are two methods available for reversing posted checks. In one, reversals are posted immediately when you click **Payment reversal** in the **Check** form. In the other, when you click **Payment reversal** in the **Check** form, the reversal first is sent to the **Check reversals** journal in Cash and bank management, where a reviewer can then post or reject the reversal.

You might reverse a check if you have to reissue a payment that you made to a vendor. You can reverse only posted checks that have a status of **Paid**. Reversing differs from deleting or voiding checks because you can delete only checks that have a status of **Created**, and you can void only unposted checks.

You can tell which method your organization uses by viewing the **Cash and bank management parameters** form. If the **Use review process for payment reversals** check box is selected, reversals are sent to the **Check reversals** journal for review.

The following table describes how the check reversal methods differ.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>If your organization does not review check reversals before posting:</p></th>
<th><p>If your organization reviews check reversals before posting:</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The check is reversed when you click <strong>OK</strong> in the <strong>Check</strong> form.</p></td>
<td><p>The check is not immediately reversed. A check reversal journal is created for review. If the check reversal journal is deleted, the check can be reversed again.</p></td>
</tr>
<tr class="even">
<td><p>The accounting entries for the original check are reversed.</p></td>
<td><p>The financial dimensions from the original check’s journal are the default financial dimensions in the check reversal journal. You can change these default values. If any posting profiles were updated after the check was posted, the check reversal journal uses the main accounts.</p></td>
</tr>
<tr class="odd">
<td><p>The accounting structures that were used when the original check was posted are used to reverse the check, even if the account structure has been changed. The account combination is not validated.</p></td>
<td><p>If an account structure changed after the original check was posted, a new financial dimension might be required for the reversal of the check. This dimension value from the original check is not the default value. The account combination is validated when the check reversal is posted.</p></td>
</tr>
<tr class="even">
<td><p>Fixed dimensions are not applied to the reversal.</p></td>
<td><p>Fixed dimensions are applied to the check reversal journal during posting. The financial dimension value might not exist in the accounting entry for the original check, depending on when the fixed dimension was defined.</p></td>
</tr>
</tbody>
</table>


## Reverse posted checks without reviewing them

If your organization wants to post check reversals immediately when you click **Payment reversal** in the **Check** form, follow these steps:

1.  Click **Cash and bank management** \> **Common** \> **Checks**.

2.  Select the check to reverse.

3.  Click **Payment reversal**.

4.  Enter the date and select a reason for the reversal.

5.  Click **OK** to post the reversal.

## Reverse posted checks after reviewing them in the check reversal journal

If your organization wants to review check reversals before posting them, follow these steps:

## Create a check reversal journal for review

1.  Click **Cash and bank management** \> **Common** \> **Checks**.

2.  Select the check to reverse.

3.  Click **Payment reversal**.

4.  Enter the date and select a reason for the reversal. You must also select a journal name to create a journal in the **Check reversals** journal.

5.  Click **OK** to send the reversal for review.

## Review a reversal

If you are a user who must review reversals, follow these steps. You can either approve and post the journal, or reject the reversal.

1.  Click **Cash and bank management** \> **Journals** \> **Check reversals**.

2.  Select the reversal journal to review, and then click **Lines**.

3.  Review the reversal and select one of the following approval options:
    
      - To approve and post the reversal journal, click **Post** or **Post and transfer**.
    
      - To reject the reversal, click **Delete journal lines**. Close the form and then click **Delete journal lines** again to delete the journal header. Close the form.


> [!NOTE]
> <P>If you delete the journal, the reversal is removed from the system, but the original check remains in the <STRONG>Check</STRONG> form. The status of the check is no longer <STRONG>Pending cancellation</STRONG>.</P>



## Results of posting a reversal

When you post a check reversal, the following occurs:

  - The check status is updated to a status of **Cancellation**.

  - If the **Reconcile** check box was selected in the reversal form during the reversal, the check is reconciled (the **Reconciled** check box is selected), and is not displayed in the **Account reconciliation** form.

  - The reversal voucher is posted against the bank account that the check was issued from, to increase the bank account balance.

  - The voucher is posted to General ledger.

  - The modification details are updated in the **History** field group in the **Check** form.


> [!NOTE]
> <P>When you reverse a check that was issued for an intercompany trade transaction, the offsetting entries come from the accounting setup for intercompany trade, not from the original transaction.</P>



If the check that was reversed was issued for a vendor payment, the following also occurs:

  - The original payment from the invoice that the payment was settled against is unapplied (the settlement is reversed).

  - A transaction is posted against the vendor account for the payment reversal, and the reversed payment is settled against the original payment. The **Last settlement voucher** field in the **Vendor transactions** form for the original vendor disbursement is updated to reflect the voucher number of the reversed transaction.

If the check that was reversed was issued for a customer payment, the following also occurs:

  - A transaction is posted against the customer account for the payment reversal, and the settlement between the original payment and the document that the payment was originally settled against is reversed (a negative payment is created).

  - A payment reversal is applied to the original payment. The **Last settlement voucher** field in the **Customer transactions** form for the original customer payment is updated to reflect the voucher number of the reversed transaction.

## See also

[Check reversals lines (form)](https://technet.microsoft.com/en-us/library/hh209241\(v=ax.60\))

[Payment reversals (form)](https://technet.microsoft.com/en-us/library/hh208702\(v=ax.60\))

[Delete a check](delete-a-check.md)

[Void unposted checks](void-unposted-checks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

