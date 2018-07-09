---
title: (IND) Transfer opening balance in excise registers using tax journals
TOCTitle: (IND) Transfer opening balance in excise registers using tax journals
ms:assetid: fdca32b6-7377-4cc0-b89f-cfed6ae05d72
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710973(v=AX.60)
ms:contentKeyID: 49386385
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Transfer opening balance in excise registers using tax journals [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Create a tax journal to complete the following tasks:

  - Transfer the opening balance of the excise components to the ledger accounts.

  - Post the adjustment entries, such as correction or modification of the excise recoverable amounts or payable amounts, between the tax components.

Refer to the following table for the form name and locators to transfer the excise balance in the RG registers.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Transaction</p></th>
<th><p>Form name and locator</p></th>
<th><p>Journal entries</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RG register</p></td>
<td><p>To transfer the excise balance in the RG registers (By Value).</p>
<p>Adjustment transaction</p></td>
<td><p><strong>General journal</strong> form (Using the Tax journal)</p>
<p>Click <strong>General ledger</strong> &gt; <strong>Journals</strong> &gt; <strong>General journal</strong>. Click <strong>Lines</strong>, and then click <strong>Functions</strong>&gt; <strong>Create tax journal</strong>.</p></td>
<td><p>Account type – Ledger (Debit)</p>
<p>Offset account type – Ledger (Credit)</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>To transfer the excise-balance in the RG register Part I or Daily Stock Accounting (DSA) register (Quantity-wise)</p></td>
<td><p><strong>Movement journal</strong> form</p>
<p>Click <strong>Inventory management</strong> &gt; <strong>Journals</strong> &gt; <strong>Item transactions</strong> &gt; <strong>Movement</strong>. Click <strong>Lines</strong>.</p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Select a journal and click the **Lines** button.

3.  Click **Functions** \> **Create tax journal**.

4.  Select the **Excise** in the **Tax type** field.

5.  Select the tax ledger posting group for excise in the **Tax ledger posting group** field.

6.  Select the excise registration number in the **Registration number** field.

7.  Enter the date the opening balance amounts are posted on in the **To date** field.

8.  Press CTRL+N to create a new line.

9.  Select the excise tax component that the opening balance amount must be transferred to in the **Tax component** field.

10. Select the ledger account that the opening balance amount is posted from in the **Account** field. If you enter a negative amount, the tax amount is deducted from the ledger account you specify in this field. If you enter a positive amount, the tax amount is added to the ledger account.

11. Enter the opening-balance amount in the **Amount** field. Enter a negative value for the credit type amount and a positive value for the debit type amount.

12. Select the tax code that the excise tax component is attached to in the **Tax code** field.

13. Click the **Transfer** button to transfer the tax journal line to the **Journal voucher** form.

14. View or modify the tax code selected in the **Create tax journal** form, which is displayed in the **Sales tax code** field on the **General** tab for the journal voucher line.

15. Select the ledger account that the opening balance transaction is posted to in the **Offset account** field.

16. Click the **Tax information** tab and select the excise record that the opening balance amount is updated to in the **Excise record type** field.

17. Validate and post the journal. The excise register is updated with the journal details and the tax component amount.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

