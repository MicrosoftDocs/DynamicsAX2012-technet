---
title: Set up deduction management
TOCTitle: Set up deduction management
ms:assetid: dae57027-b5f6-467d-9850-0259d5abfcb0
ms:mtpsurl: https://technet.microsoft.com/library/Dn497836(v=AX.60)
ms:contentKeyID: 62200168
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- deductions
- Forms.TAMDeduction
- Forms.TAMDeductionType
- Forms.TAMDeductionWriteOffReason
- Forms.TAMDeductionDenyReason
- MsDynAx060.Forms.TAMDeductionDenyReason
- MsDynAx060.Forms.TAMDeductionType
- MsDynAx060.Forms.TAMDeductionWriteOffReason
- MsDynAx060.Forms.TAMDeduction
- rebates
- deduction workbench
- deductions workbench
audience: Application User
ms.search.region: Global
---

# Set up deduction management 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up the deduction workbench so that you can process customer payments that include deductions.

A customer who is owed a rebate can decide not to wait for a rebate payout. Instead, the customer can send a payment that includes a deduction for the amount of the rebate. To handle this type of transaction, you can use the deduction workbench to match deductions to open credit transactions, split deductions, deny deductions, and write off deductions.

Before you can use the workbench, you must set up a deduction journal, deduction types, deduction denial reasons, and deduction write-off reasons.

## 1\. Specify a deduction journal

You must specify a deduction journal in the **Trade allowance management parameters** form. This journal is used to match, deny, or write off deductions. You can also specify whether the journal is posted manually or automatically.

To specify a deduction journal, follow these steps.

1.  Click **Trade allowance management** \> **Setup** \> **Trade allowance management parameters**.

2.  On the **Deductions** FastTab, in the **Deduction journal name** field, select a journal.

## 2\. Set up deduction types

You can create deduction types to describe the various types of rebates that customers might use.

To set up deduction types, follow these steps.

1.  Click **Trade allowance management** \> **Setup** \> **Deductions** \> **Deduction types**.

2.  Click **New**, and then enter a name and description for the deduction type. In the **Deduction offset** field, select the offset account to use when you post, match, or write off a deduction.

3.  Repeat step 2 to create all the deduction types that you require.

## 3\. Set up deduction denial reasons

You can set up reason codes to describe the various reasons for denying a deduction in the deduction workbench.

To set up deduction denial reasons, follow these steps.

1.  Click **Trade allowance management** \> **Setup** \> **Deductions** \> **Deduction denial reasons**.

2.  Click **New**, and then enter a reason code and a description.

3.  Repeat step 2 to add all the reason codes that you require.

## 4\. Set up deduction write-off reasons

You can set up reason codes to describe the various reasons for writing off a deduction in the deduction workbench.

To set up deduction write-off reasons, follow these steps.

1.  Click **Trade allowance management** \> **Setup** \> **Deductions** \> **Deduction write-off reasons**.

2.  Click **New**, and then enter a reason code and a description.

3.  Enter the maximum write-off amount that is allowed for the reason code. A value of **0** indicates that there is no maximum amount.

4.  Enter the main account to use for posting in the ledger.

5.  Repeat steps 2 through 4 to add all the reason codes that you require.

## Next step

After you set up a deduction journal, deduction types, and reason codes, you can use the deduction workbench. For more information, see [Manage deductions in the deduction workbench](manage-deductions-in-the-deduction-workbench.md).

## Related tasks

[Setting up and maintaining customer rebates](setting-up-and-maintaining-customer-rebates.md)

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
<td><p><strong>Trade allowance management</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>Collections manager</p></td>
</tr>
</tbody>
</table>


## See also

[Manage deductions in the deduction workbench](manage-deductions-in-the-deduction-workbench.md)

  


