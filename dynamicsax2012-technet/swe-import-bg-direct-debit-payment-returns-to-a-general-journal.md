---
title: (SWE) Import BG direct debit payment returns to a general journal
TOCTitle: (SWE) Import BG direct debit payment returns to a general journal
ms:assetid: d99cc4fd-e7ea-45e8-ae29-7d80a857aaa3
ms:mtpsurl: https://technet.microsoft.com/library/Hh227401(v=AX.60)
ms:contentKeyID: 36059655
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Sweden
- Bankgirot
- direct debit
- BG
audience: Application User
ms.search.region: Sweden
---

# (SWE) Import BG direct debit payment returns to a general journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Bank Giro Centralen (BGC) of Sweden has updated the Bank Giro (BG) direct debit payment format to include refund requests. You can export the direct debit payment details to the BG direct debit payment file and import the direct debit payment returns to a general journal for validation and posting.

Each time that you import a BG direct debit payment return file, a new transaction is created in the general journal. If you import a payment that already exists in the journal, a duplicate transaction is created for that payment return file. You can also settle payments with an open credit invoice.

## Prerequisites

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Conditions</p></th>
<th><p>Cross-reference</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create and post a sales invoice for a Swedish customer</p></td>
<td><p>N/A</p></td>
<td><p><a href="key-tasks-customer-invoices.md">Key tasks: Customer invoices</a></p></td>
</tr>
<tr class="even">
<td><p>Create a payment journal for the sales invoice</p></td>
<td><ul>
<li><p>On the <strong>Overview</strong> tab of the <strong>Journal voucher</strong> form, in the <strong>Offset account type</strong> field, select <strong>Bank</strong>.</p></li>
</ul>
<ul>
<li><p>In the <strong>Offset account</strong> field, select the bank account for BG direct debit payments.</p></li>
</ul>
<ul>
<li><p>Verify that the <strong>Currency</strong> field is set to <strong>SEK</strong> and the <strong>Method of payment</strong> field is set to the method of payment created for BG direct debit payments.</p>
<p>Do not post the payment journal.</p></li>
</ul>
<p></p></td>
<td><p><a href="key-tasks-customer-payments-and-settlements.md">Key tasks: Customer payments and settlements</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a BG direct debit payment file</p></td>
<td><ul>
<li><p>In the <strong>Generate payments</strong> form, select the method of payment that is set up for BG direct debit payments in the <strong>Method of payment</strong> field.</p></li>
</ul>
<ul>
<li><p>In the <strong>Export format</strong> field, select <strong>Bank giro Autogiro (SE)</strong>.</p></li>
</ul>
<ul>
<li><p>In the <strong>Bankgirot Autogiro (SE)</strong> form, type the path and the name of the payment file in the <strong>File name</strong> field.</p></li>
</ul>
<p></p></td>
<td><p><a href="create-an-electronic-payment-file-for-customers.md">Create an electronic payment file for customers</a></p></td>
</tr>
</tbody>
</table>


## Import and post the BG direct debit payment returns

Use the **Load diskette with payments** form to import refunds for the BG direct debit return file. If the return file already contains refund information, you can select the **Import refunds** check box and specify the name of the general journal to be used for the import. If the return file contains refund information but the **Import refunds** check box is cleared, you must import the return file again to import the refunds. You can then view the new transaction.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment transfers**.

2.  Click **Return file - customer** to open the **Load diskette with payments** form.

3.  In the **Method of payment** field, select the method of payment that is set up to use the Bank giro Autogiro (SE) import format, and then click **OK** to open the **Bankgirot Autogiro (SE)** form.

4.  In the **File name** field, type the path and the name of the import file, or browse to select the import file on your computer or network.

5.  Select the **Import refunds** check box to import the refunds from the import file. If you clear the **Import refunds** check box and the import file already contains refunds, a message is displayed.

6.  In the **New journal name** field, select the name of the journal used to import refund details. The description of the journal name is automatically displayed in the **New journal description** field.

7.  Click **OK** to save and close the **Bankgirot Autogiro (SE)** form. A new general journal is created and the results are imported.

8.  Click **General ledger** \> **Journals** \> **General journal**.

9.  Select the journal created for the refund transaction, and then click **Lines**.

10. In the **Journal voucher** form select the journal line to validate for posting, and then click **Validate** \> **Validate** to validate the journal. . For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

11. Click **Post** \> **Post** to post the journal.

12. Close the form to save your changes.

## See also

[(SWE) Bank Giro Autogiro (form)](https://technet.microsoft.com/library/hh227647\(v=ax.60\))

[(SWE) Set up a bank account for BG direct debit payments](swe-set-up-a-bank-account-for-bg-direct-debit-payments.md)

[(SWE) Set up the BG direct debit method of payment for a customer](swe-set-up-the-bg-direct-debit-method-of-payment-for-a-customer.md)

  


