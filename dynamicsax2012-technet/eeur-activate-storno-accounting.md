---
title: (EEUR) Activate storno accounting
TOCTitle: (EEUR) Activate storno accounting
ms:assetid: ab3dab82-7f40-4315-95bf-f002e4d7d4d7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ852136(v=AX.60)
ms:contentKeyID: 50281222
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- parameters
- correction
- storno
- Eastern Europe
- red storno
---

# (EEUR) Activate storno accounting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use these procedures to set up storno accounting in Microsoft Dynamics AX. In storno accounting, you reverse the sign on amounts to reverse incorrect original transactions. For example, the following transactions are incorrectly recorded.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Description</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales revenue</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


To reverse the transactions and post the reversing transactions as storno transactions, you enter the following information.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Description</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales revenue</p></td>
<td><p></p></td>
<td><p>-100.00</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p>-100.00</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


Each reversing transaction appears in the same debit or credit column as the original transaction. By keeping amounts in their original columns and reversing the sign on the amounts, you effectively “zero out” the original transaction.

After you complete the following procedure, Microsoft Dynamics AX automatically creates transaction reversals as storno transactions.

## Activate storno accounting system-wide

You must activate storno accounting in General ledger before you can set up storno parameters in any module.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the **Ledger** area, on the **Accounting rules** FastTab, in the **Transaction reversal** field group, select the **Correction** check box.

## Activate storno accounting in application modules

After you activate storno accounting in General ledger, you can set up parameters in the application modules. The parameters that are specific to a module typically use storno accounting by default for various processes in the module. You can change the default setting when it appears in a form. However, the setting does not appear in all forms. Some forms always use the default setting during processing, and you cannot change the setting.

## Set up storno accounting in Accounts payable

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  In the **Invoice** area, in the **Invoice** field group, select the **Credit note as correction** check box. By default, credit notes are now posted as storno transactions.

## Set up storno accounting in Accounts receivable

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Updates** area, in the **Advance invoice** field group, select the **Credit note as correction** check box. By default, credit notes for advance invoices are now posted as storno transactions.

3.  Select the **Reversal as correction** check box. By default, reversals for advance invoices are now posted as storno transactions.

4.  In the **Invoice** field group, select the **Credit note as correction** check box. By default, credit notes for invoices are now posted as storno transactions.

## Set up storno accounting in Inventory and warehouse management

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  In the **General** area, in the **Correction** field group, select the **Inventory adjustment – correction** check box. By default, adjustments to inventory are now posted as storno transactions.

## Set up storno accounting in Project management and accounting

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the **General** area, in the **Adjustment** field group, select the **Adjustment of project transactions – correction** check box. By default, adjustments to project transactions are now posted as storno transactions.

3.  In the **Journals** area, in the **Ledger posting** field group, select the **Negative transactions – correction** check box. By default, project journal entries that have a negative cost amount are now posted as storno transactions.

## See also

[General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\))

[(EEUR) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710686\(v=ax.60\))

[(CZE) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj838779\(v=ax.60\))

[(LTU) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj911001\(v=ax.60\))

[Accounts payable parameters (form)](https://technet.microsoft.com/en-us/library/aa596348\(v=ax.60\))

[(EEUR) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj720358\(v=ax.60\))

[(CZE) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710667\(v=ax.60\))

[(HUN) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj664360\(v=ax.60\))

[(LTU) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj665154\(v=ax.60\))

[(LVA) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj731039\(v=ax.60\))

[(POL) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj678134\(v=ax.60\))

[Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\))

[(EEUR) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710793\(v=ax.60\))

[(CZE) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj677464\(v=ax.60\))

[(HUN) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj714534\(v=ax.60\))

[(LTU) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj665084\(v=ax.60\))

[(LVA) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj731076\(v=ax.60\))

[(POL) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj678183\(v=ax.60\))

[Inventory and warehouse management parameters (form)](https://technet.microsoft.com/en-us/library/aa587658\(v=ax.60\))

[(EEUR) Inventory and warehouse management parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710787\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

[(EEUR) Project management and accounting parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710688\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

