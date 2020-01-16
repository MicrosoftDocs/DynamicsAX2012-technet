---
title: About ledger journal types
TOCTitle: About ledger journal types
ms:assetid: 648ccf23-3a92-49c4-b471-03976fba293d
ms:mtpsurl: https://technet.microsoft.com/library/Aa585226(v=AX.60)
ms:contentKeyID: 44080988
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About ledger journal types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the journal types that you can set up for financial journals. Use the **Journal names** form to set up journals that you can use throughout Microsoft Dynamics AX. (Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.) You can set up the following types of journals.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Journal type</p></th>
<th><p>Purpose</p></th>
<th><p>Additional information</p></th>
<th><p>Form in which to enter transactions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Allocation</strong></p></td>
<td><p>Create allocation transactions in an allocations journal.</p></td>
<td><p>You must create an allocation rule in the <strong>Ledger allocation rule</strong> form before you can create an allocation journal.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="process-an-allocation-request.md">Process an allocation request</a></p></li>
<li><p><a href="create-an-allocation-journal.md">Create an allocation journal</a></p></li>
</ul></td>
<td><p><strong>Process allocation request</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Amount difference</strong></p></td>
<td><p>(RUS) Create and link amount difference factures to an original purchase invoice or to an original sales invoice.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-amount-difference-parameters-for-exchange-rates.md">(RUS) Set up amount difference parameters for exchange rates</a></p></li>
<li><p><a href="rus-create-and-link-an-amount-difference-facture-to-an-original-purchase-invoice.md">(RUS) Create and link an amount difference facture to an original purchase invoice</a></p></li>
<li><p><a href="rus-create-and-link-an-amount-difference-facture-to-an-original-sales-invoice.md">(RUS) Create and link an amount difference facture to an original sales invoice</a></p></li>
<li><p><a href="rus-reverse-a-ledger-journal-of-amount-difference-transactions.md">(RUS) Reverse a ledger journal of amount difference transactions</a></p></li>
</ul></td>
<td><p><strong>Facture</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Approval</strong></p></td>
<td><p>Post vendor invoices that have been approved to the appropriate ledger accounts.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="post-invoices-in-the-invoice-approval-journal-form.md">Post invoices in the Invoice approval journal form</a></p></li>
<li><p><a href="ind-post-transactions-for-customs-in-the-invoice-approval-journal-form.md">(IND) Post transactions for customs in the Invoice approval journal form</a></p></li>
<li><p><a href="ind-post-purchase-transactions-of-excise-using-the-invoice-approval-journal-form.md">(IND) Post purchase transactions of excise using the Invoice approval journal form</a></p></li>
<li><p><a href="ind-post-service-tax-in-purchase-transactions-by-using-the-invoice-approval-journal-form.md">(IND) Post service tax in purchase transactions by using the Invoice approval journal form</a></p></li>
</ul></td>
<td><p><strong>Invoice approval journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Assessed tax</strong></p></td>
<td><p>(RUS) Create a ledger journal of assessed tax transactions for Fixed assets (Russia).</p>
<p>– and –</p>
<p>(RUS) Calculate the depreciation bonus recovery register.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-the-calculation-of-assessed-tax.md">(RUS) Set up the calculation of assessed tax</a></p></li>
<li><p><a href="rus-set-up-the-name-for-fixed-asset-tax-transactions-journals.md">(RUS) Set up the name for fixed asset tax transactions journals</a></p></li>
<li><p><a href="rus-create-a-ledger-journal-of-assessed-tax-transactions.md">(RUS) Create a ledger journal of assessed tax transactions</a></p></li>
<li><p><a href="rus-calculate-assessed-tax-registers.md">(RUS) Calculate assessed tax registers</a></p></li>
<li><p><a href="rus-calculate-the-depreciation-bonus-recovery-register.md">(RUS) Calculate the depreciation bonus recovery register</a></p></li>
</ul></td>
<td><p><strong>Tax register journal</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank check reversal</strong></p></td>
<td><p>Reverse a posted check.</p></td>
<td><p>Select the <strong>Use review process for payment reversals</strong> check box in the <strong>Cash and bank management parameters</strong> form to use this journal type.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="set-up-a-review-process-for-reversals-and-cancellations.md">Set up a review process for reversals and cancellations</a></p></li>
<li><p><a href="reverse-a-posted-check.md">Reverse a posted check</a></p></li>
</ul></td>
<td><p><strong>Check reversals</strong> form</p>
<p><strong>Payment reversal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank deposit slip cancellation</strong></p></td>
<td><p>Cancel a deposit slip.</p></td>
<td><p>Select the <strong>Use review process for deposit slip payment cancellations</strong> check box in the <strong>Cash and bank management parameters</strong> form to use this journal type.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="set-up-a-review-process-for-reversals-and-cancellations.md">Set up a review process for reversals and cancellations</a></p></li>
<li><p><a href="cancel-a-deposit-slip-payment.md">Cancel a deposit slip payment</a></p></li>
</ul></td>
<td><p><strong>Deposit slip payment cancellations</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Budget</strong></p></td>
<td><p>Process budget appropriations.</p></td>
<td><p>Select the <strong>Enable budget appropriation</strong> check box in the <strong>General ledger parameters</strong> form to use this journal type. The budget journal entries will include information that is based on the ledger accounts that are defined in the <strong>Posting definitions</strong> form.</p>
<p>For more information, see <a href="define-budgeting-parameters-and-number-sequences.md">Define Budgeting parameters and number sequences</a>.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Cash</strong></p></td>
<td><p>(LTU) Register cash transactions.</p>
<p>– and –</p>
<p>(RUS) Post retail transactions.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-a-cash-journal-for-cash-disbursement-and-reimbursement.md">(RUS) Set up a cash journal for cash disbursement and reimbursement</a></p></li>
<li><p><a href="rus-prepayments-in-retail-for-russia.md">(RUS) Prepayments in Retail for Russia</a></p></li>
<li><p><a href="rus-register-reimbursement-or-disbursement-slips.md">(RUS) Register reimbursement or disbursement slips</a></p></li>
<li><p><a href="ltu-generate-a-cash-reimbursement-slip.md">(LTU) Generate a cash reimbursement slip</a></p></li>
</ul></td>
<td><p><strong>Journal voucher</strong> form</p>
<p><strong>Slip journal</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer accept bill of exchange</strong></p></td>
<td><p>Create customer acceptance transactions for bills of exchange.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="draw-a-bill-of-exchange.md">Draw a bill of exchange</a></p></li>
<li><p><a href="jpn-create-and-endorse-a-bill-of-exchange.md">(JPN) Create and endorse a bill of exchange</a></p></li>
</ul></td>
<td><p><strong>Draw bill of exchange journal</strong> form</p>
<p><strong>Redraw bill of exchange journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer bank remittance</strong></p></td>
<td><p>Create a bill of exchange remittance file that can be sent to your organization’s bank.</p></td>
<td><p>Clear the <strong>Automatic settlement</strong> check box in the <strong>Accounts receivable parameters</strong> form to use this journal type.</p>
<p>For more information, see <a href="remit-a-bill-of-exchange.md">Remit a bill of exchange</a>.</p></td>
<td><p><strong>Remittance</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer draw bill of exchange</strong></p></td>
<td><p>Create customer draw bill of exchange transactions.</p></td>
<td><p>Clear the <strong>Create and post draw journal automatically when posting invoices</strong> check box in the <strong>Methods of payment - customers</strong> form to use this journal type.</p>
<p>For more information, see <a href="draw-a-bill-of-exchange.md">Draw a bill of exchange</a>.</p></td>
<td><p><strong>Draw bill of exchange journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer payment</strong></p></td>
<td><p>Create customer payment transactions.</p></td>
<td><p>For more information, see <a href="enter-and-settle-customer-payments-in-a-payment-journal.md">Enter and settle customer payments in a payment journal</a>.</p></td>
<td><p><strong>Payment journal</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer protest bill of exchange</strong></p></td>
<td><p>Create customer protest bill of exchange transactions.</p></td>
<td><p>For more information, see <a href="protest-a-bill-of-exchange.md">Protest a bill of exchange</a>.</p></td>
<td><p><strong>Protest bill of exchange journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer redraw bill of exchange</strong></p></td>
<td><p>Create customer redraw bill of exchange transactions.</p></td>
<td><p>For more information, see <a href="redraw-a-bill-of-exchange.md">Redraw a bill of exchange</a>.</p></td>
<td><p><strong>Redraw bill of exchange journal</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer settle bill of exchange</strong></p></td>
<td><p>Create customer settle bill of exchange transactions.</p></td>
<td><p>For more information, see <a href="settle-a-bill-of-exchange.md">Settle a bill of exchange</a>.</p></td>
<td><p><strong>Settle bill of exchange journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Daily</strong></p></td>
<td><p>Create daily transactions in a general journal.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="setting-up-and-maintaining-journals.md">Setting up and maintaining journals</a></p></li>
<li><p><a href="chn-set-up-a-chinese-voucher-system.md">(CHN) Set up a Chinese voucher system</a></p></li>
<li><p><a href="jpn-set-up-positive-debit-and-credit-amounts.md">(JPN) Set up positive debit and credit amounts</a></p></li>
</ul></td>
<td><p><strong>General journal</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Deferrals</strong></p></td>
<td><p>(RUS) Generate deferrals write-off vouchers.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="https://technet.microsoft.com/library/jj839697(v=ax.60)">(RUS) Deferrals counting journal (form)</a></p></li>
<li><p><a href="rus-dispose-of-deferrals-vouchers.md">(RUS) Dispose of deferrals vouchers</a></p></li>
<li><p><a href="rus-generate-a-deferrals-write-off-voucher-for-all-deferrals.md">(RUS) Generate a deferrals write-off voucher for all deferrals</a></p></li>
<li><p><a href="rus-generate-a-deferrals-write-off-voucher-for-one-deferral.md">(RUS) Generate a deferrals write-off voucher for one deferral</a></p></li>
<li><p><a href="rus-generate-and-print-an-inventory-act-inv-11-report.md">(RUS) Generate and print an Inventory act (INV-11) report</a></p></li>
</ul></td>
<td><p><strong>Deferrals counting journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Elimination</strong></p></td>
<td><p>Create elimination transactions in an eliminations journal.</p></td>
<td><p>Select the <strong>Use for financial elimination process</strong> check box and the <strong>Use for financial consolidation process</strong> check box in the <strong>Legal entities</strong> form to use this journal type.</p>
<p>You must create a ledger elimination rule in the <strong>Ledger elimination rule</strong> form before you can use this journal type.</p>
<p>For more information, see <a href="eliminate-transactions.md">Eliminate transactions</a>.</p></td>
<td><p><strong>Elimination</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Fixed asset budget</strong></p></td>
<td><p>Create fixed asset budget register entries.</p></td>
<td><p>For more information, see <a href="post-fixed-asset-budgets.md">Post fixed asset budgets</a>.</p></td>
<td><p><strong>Fixed asset budget</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice register</strong></p></td>
<td><p>Register basic information about vendor invoices.</p></td>
<td><p>For more information, see <a href="enter-and-post-invoices-in-the-invoice-register-form.md">Enter and post invoices in the Invoice register form</a>.</p></td>
<td><p><strong>Invoice register</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Land tax</strong></p></td>
<td><p>(RUS) Generate land tax transactions.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-the-calculation-of-land-tax.md">(RUS) Set up the calculation of land tax</a></p></li>
<li><p><a href="rus-set-up-the-name-for-fixed-asset-tax-transactions-journals.md">(RUS) Set up the name for fixed asset tax transactions journals</a></p></li>
<li><p><a href="rus-calculate-land-tax-registers.md">(RUS) Calculate land tax registers</a></p></li>
</ul></td>
<td><p><strong>Tax register journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Payroll disbursement</strong></p></td>
<td><p>Issue payments based on Payroll pay statements.</p></td>
<td><p>You can’t manually enter transactions in this journal. You must generate pay statements and then submit those statements for payment.</p>
<p>This journal type is available only if you are using Microsoft Dynamics AX 2012 R2.</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Periodic</strong></p></td>
<td><p>Create periodic transactions for the periodic journal.</p>
<p>– and –</p>
<p>(EEUR) Create and post a periodic journal by specifying the period interval for the recurrence, such as days or months.</p></td>
<td><p>For more information, see <a href="eeur-create-and-post-a-periodic-journal.md">(EEUR) Create and post a periodic journal</a>.</p></td>
<td><p><strong>Periodic journals</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Post fixed assets</strong></p></td>
<td><p>Post fixed asset transactions.</p></td>
<td><p>For more information, see <a href="post-fixed-asset-journals.md">Post fixed asset journals</a>.</p></td>
<td><p><strong>Fixed assets</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project - expenses</strong></p></td>
<td><p>Create project expense transactions.</p></td>
<td><p>For more information, see <a href="about-project-transactions.md">About project transactions</a>.</p></td>
<td><p><strong>Expense</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Statistic transactions</strong></p></td>
<td><p>Create statistical transactions.</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Tax cost price</strong></p></td>
<td><p>(RUS) Create a tax cost price journal.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-journal-names-and-number-sequences-for-tax-cost-price-journals.md">(RUS) Set up journal names and number sequences for tax cost price journals</a></p></li>
<li><p><a href="rus-create-a-tax-cost-price-journal.md">(RUS) Create a tax cost price journal</a></p></li>
<li><p><a href="rus-calculate-and-approve-the-wip-and-fp-estimate-in-a-tax-accounting-register.md">(RUS) Calculate and approve the WIP and FP estimate in a tax accounting register</a></p></li>
</ul></td>
<td><p><strong>Tax register journal</strong> form</p>
<p></p></td>
</tr>
<tr class="even">
<td><p><strong>Tax differences</strong></p></td>
<td><p>(RUS) Create ledger journals of tax difference transactions.</p>
<p>– and –</p>
<p>(RUS) Calculate the depreciation bonus recovery register.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-journal-names-and-number-sequences-for-tax-cost-price-journals.md">(RUS) Set up journal names and number sequences for tax cost price journals</a></p></li>
<li><p><a href="rus-create-a-tax-cost-price-journal.md">(RUS) Create a tax cost price journal</a></p></li>
<li><p><a href="rus-reverse-a-ledger-journal-of-tax-difference-transactions.md">(RUS) Reverse a ledger journal of tax difference transactions</a></p></li>
</ul></td>
<td><p><strong>Tax register journal</strong> form</p>
<p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Transport tax</strong></p></td>
<td><p>(RUS) Calculate the total transport tax amount and the advance transport tax payments.</p>
<p>– and –</p>
<p>(RUS) Create a transport tax declaration.</p></td>
<td><p>For more information, see the following topics:</p>
<ul>
<li><p><a href="rus-set-up-the-calculation-of-transport-tax.md">(RUS) Set up the calculation of transport tax</a></p></li>
<li><p><a href="rus-set-up-the-name-for-fixed-asset-tax-transactions-journals.md">(RUS) Set up the name for fixed asset tax transactions journals</a></p></li>
<li><p><a href="rus-create-a-transport-tax-declaration.md">(RUS) Create a transport tax declaration</a></p></li>
<li><p><a href="rus-calculate-transport-tax-registers.md">(RUS) Calculate transport tax registers</a></p></li>
<li><p><a href="rus-create-a-ledger-journal-of-transport-tax-transactions.md">(RUS) Create a ledger journal of transport tax transactions</a></p></li>
</ul></td>
<td><p><strong>Tax register journal</strong> <strong>Tax register journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor bank remittance</strong></p></td>
<td><p>Create a promissory note remittance file that can be sent to your organization’s bank.</p></td>
<td><p>For more information, see <a href="remit-a-promissory-note.md">Remit a promissory note</a>.</p></td>
<td><p><strong>Remittance journal</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor disbursement</strong></p></td>
<td><p>Create vendor disbursement transactions.</p></td>
<td><p>For more information, see <a href="select-vendor-invoices-to-pay-and-settle.md">Select vendor invoices to pay and settle</a>.</p></td>
<td><p><strong>Payment journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor draw promissory note</strong></p></td>
<td><p>Draw vendor promissory notes as a method of payment.</p></td>
<td><p>Clear the <strong>Create and post draw journal automatically when posting invoices</strong> check box in the <strong>Methods of payment - vendors</strong> form to use this journal type.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="draw-a-promissory-note.md">Draw a promissory note</a></p></li>
<li><p><a href="esp-generate-a-promissory-note-by-using-a-free-promissory-note-number-method.md">(ESP) Generate a promissory note by using a free promissory note number method</a></p></li>
</ul></td>
<td><p><strong>Draw promissory note journal</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor invoice pool excl. posting</strong></p></td>
<td><p>Create vendor invoice transactions that have not yet been posted to a temporary arrival account.</p></td>
<td><p>For more information, see <a href="enter-vendor-invoices-in-an-invoice-pool.md">Enter vendor invoices in an invoice pool</a>.</p></td>
<td><p><strong>Vendor invoice pool excluding posting details</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor invoice pool</strong></p></td>
<td><p>Create vendor invoice pool transactions.</p></td>
<td><p>For more information, see <a href="post-vendor-invoices-that-are-in-an-invoice-pool.md">Post vendor invoices that are in an invoice pool</a>.</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor invoice recording</strong></p></td>
<td><p>Post vendor invoices that are in a journal.</p></td>
<td><p>For more information, see <a href="enter-vendor-invoices-in-journals.md">Enter vendor invoices in journals</a>.</p></td>
<td><p><strong>Invoice journal</strong> form</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor redraw promissory note</strong></p></td>
<td><p>Redraw a promissory note that has been previously honored by your organization’s bank.</p></td>
<td><p>For more information, see <a href="redraw-a-promissory-note.md">Redraw a promissory note</a>.</p></td>
<td><p><strong>Redraw promissory note journal</strong> form</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor settle promissory note</strong></p></td>
<td><p>Create vendor settle promissory note transactions.</p></td>
<td><p>For more information, see <a href="settle-a-promissory-note.md">Settle a promissory note</a>.</p></td>
<td><p><strong>Settle promissory note journal</strong> form</p></td>
</tr>
</tbody>
</table>

  


