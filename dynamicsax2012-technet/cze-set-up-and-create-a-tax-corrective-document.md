---
title: (CZE) Set up and create a tax corrective document
TOCTitle: (CZE) Set up and create a tax corrective document
ms:assetid: f4303358-404d-4996-b198-c6559c392b49
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn494957(v=AX.60)
ms:contentKeyID: 60508155
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.ProjCreditNoteSelect
- Forms.Reasons
- Forms.CustParameters
- Forms.CustFreeInvoiceListPage
- Forms.SalesTableListPage
- Forms.ProjProjectsListPage
- Forms.ProjTable
- Forms.SalesTable
- Forms.ProjInvoiceJournal
- Forms.CustFreeInvoice
- Forms.LedgerParameters
- Forms.SalesEditLines
- Forms.SalesCopying
- Forms.ProjInvoiceProposalCreateLines
- CZ - 00017
- Czech Republic
- Forms.CustFreeCreditNote_W
- sales discount
- sales return
- tax corrective document
- VAT correction
---

# (CZE) Set up and create a tax corrective document [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a tax corrective document for sales returns, cash discounts, and value-added tax (VAT) corrections when the amount that the customer pays is lower than the amount on the sales invoice. You can include the following information in the tax corrective document for customer invoices, free text invoices, and project invoices:

  - The invoice number of the sales invoice

  - The VAT base amount and the amount of the sales invoice

  - A reason for the correction


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



Use the following procedures to set up and create a tax corrective document.

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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Czech Republic</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related tasks</strong></p></td>
<td><ul>
<li><p>Create and post a sales order. For more information, see <a href="create-or-edit-a-sales-order.md">Create or edit a sales order</a> and <a href="https://technet.microsoft.com/en-us/library/jj714420(v=ax.60)">(CZE) Sales orders (modified form)</a>.</p></li>
<li><p>Create and post a free text invoice. For more information, see <a href="key-tasks-free-text-invoices.md">Key tasks: Free text invoices</a> and <a href="https://technet.microsoft.com/en-us/library/jj677647(v=ax.60)">(CZE) Free text invoice (modified form)</a>.</p></li>
<li><p>Create and post a project invoice. For more information, see <a href="create-an-invoice-for-a-time-and-material-project.md">Create an invoice for a time and material project</a>, <a href="create-an-invoice-for-a-fixed-price-project.md">Create an invoice for a fixed-price project</a>, and <a href="create-and-post-invoice-proposals.md">Create and post invoice proposals</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a reason code for the tax corrective document

Use the **Customer reasons** form to set up a default reason code that is used for tax corrective documents.

To set up a reason code, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer reasons**.

2.  Click **New** to create a reason code for the tax corrective document. For more information, see the “Accounts receivable” section in [Set up reason codes for financial modules](set-up-reason-codes-for-financial-modules.md).

3.  Ensure that the **Customer** check box is selected for the reason code.

## 2\. Set up the parameter for cash discounts

Use the **General ledger parameters** form to set up the parameter to reverse sales tax for cash discounts.

To set up the parameter for cash discounts, follow these steps:

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the left pane, click **Sales tax**, and then in the **Sales tax** area, on the **Tax options** FastTab, select the **Reverse sales tax on cash discount** check box. The sales tax amount that is calculated is reversed for the cash discount amount.

## 3\. Set up the parameters for cash discount credit notes

Use the **Accounts receivable parameters** form to set up the parameters for credit notes.

To set up the parameters for credit notes, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **General** area, on the **Reason code requirements** FastTab, select the **Require reasons for credit notes** check box to add reason codes for credit notes.

3.  In the left pane, click **Settlement**, and in the **Settlement** area, in the **Settlement** field group, select the **Post credit note for cash discount** check box to post credit notes for cash discounts.

4.  In the **Reason code for cash discounts** field, select the customer reason code for cash discounts.
    

    > [!NOTE]
    > <P>The <STRONG>Reason code for cash discounts</STRONG> field is available only if you select the <STRONG>Post credit note for cash discount</STRONG> check box.</P>



## 4\. Create and post a credit note for a customer invoice by providing a reason

Use the **Create credit note** form to create a credit note for a customer invoice and provide a reason for the correction.

To create and post a credit note, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click the sales order to create the credit note for, and on the **Action Pane**, on the **Sell** tab, click **Credit note**.

3.  In the **Reason code** field, select the identification code for the reason that describes why the customer invoice is corrected.

4.  In the **Reason comment** field, enter or update the reason for the customer invoice correction.

5.  Select the **Create corrective lines** check box to create both the corrected and the corrective lines for the customer invoice.

6.  On the **Invoice** tab, select the **Select all** check box to select all of the sales order lines. Alternatively, you can select the **Mark** check box to select individual sales order lines.

7.  In the **Amount** field, modify the amount of the invoice, if required.

8.  Click **OK** to create and post the credit note transactions. The **Sales order** form displays the corrected and corrective lines.

9.  In the **Sales order** form, on the **Line details** FastTab, on the **Setup** tab, in the **Sales tax group** and **Item sales tax group** fields, modify the sales tax group and the item sales tax group for the corrected lines, if required.

10. In the **Reason code** field, modify the identification code for the reason that describes why the customer invoice line is corrected, if required.

11. On the **Invoice** tab, in the **Generate** group, click **Invoice**.

12. In the **Posting invoice** form, select the **Posting** and **Print invoice** check boxes to post and print the invoice.

## 5\. Create and post a credit note for a free text invoice by providing a reason

Use the **Create credit note** form to create a credit note for a free text invoice and provide a reason for the correction.

To create and post a credit note, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Double-click the free text invoice to create the credit note for, and on the **Action Pane**, in the **Sell** group, click **Cancel** \> **Create credit note**.

3.  In the **Reason code** field, select the identification code for the reason that describes why the free text invoice is corrected.

4.  In the **Reason comment** field, enter or update the reason for the free text invoice correction.

5.  Select the **Create corrective lines** check box to create both the corrected and the corrective lines for the free text invoice.

6.  On the **Invoice** tab, in the upper pane, select the **Mark** check box to select all of the free text invoice lines. Alternatively, on the **Invoice lines** tab, in the lower pane, select the **Mark** check box to select individual free text invoice lines.

7.  Click **OK** to create credit note transactions for the free text invoice. The **Free text invoice** form displays the corrected and corrective lines.

8.  In the **Free text invoice** form, in the **Sales tax group** and **Item sales tax group** fields, modify the sales tax group and the item sales tax group for the corrected line, if required.

9.  In the **Reason code** field, modify the identification code for the reason that describes why the customer invoice line is corrected, if required.

10. Make any required changes to the corrective line, such as in the **Amount** field, modify the amount of the invoice line.

11. On the **Action Pane**, click **Post** \> **Post** to post the corrected invoice.

## 6\. Create and post a credit note for a project invoice by providing a reason

Use the **Create invoice proposal** form to create a credit note for a project invoice and provide a reason for the correction.

To create and post a credit note, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Double-click a project invoice to create the credit note for.

3.  Create, adjust, and post a transaction by using an hour, expense, or fee journal. For more information, see [Journal lines for hours (form)](https://technet.microsoft.com/en-us/library/aa571787\(v=ax.60\)), [Expense journal (form)](https://technet.microsoft.com/en-us/library/aa600976\(v=ax.60\)), and [Journal lines for fees (form)](https://technet.microsoft.com/en-us/library/aa498986\(v=ax.60\)).

4.  In the **Projects** form, on the **Manage** tab, click **Invoice journals**.

5.  In the **Invoice journals** form, select an invoice journal line, and then click **Functions** \> **Select for credit note**.

6.  In the **Select for credit note** form, select the **Select** check box to specify the project invoice transactions for the credit note.

7.  Click **OK**.

8.  In the **Projects** form, on the **Manage** tab, click **Invoice proposal**.

9.  In the **Create invoice proposal** form, select the invoices to include in the credit note.

10. In the **Reason code** field, select the identification code for the reason that describes why the project invoice is corrected.

11. In the **Reason comment** field, enter or update the reason for the project invoice correction, and then click **OK** to post the credit note for the project invoice.

## Create and post a credit note for a cash discount

You can create a credit note for a cash discount that you posted for a sales order, a free text invoice, or a project invoice. For more information about how to post a cash discount, see [Scenario: Cash discount handling for overpayments](scenario-cash-discount-handling-for-overpayments.md).

You can use the **Payment journal** and **Journal voucher** forms to create and post a payment for the invoice that you posted for a cash discount. When you post the payment journal, the payment is posted, the cash discount is reversed, and AX 2012 R2 creates a credit note automatically. You can print the credit note from the **Invoice journal** form. For more information, see [Enter and settle customer payments in a payment journal](enter-and-settle-customer-payments-in-a-payment-journal.md), [Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\)), [Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/en-us/library/aa556141\(v=ax.60\)), and [(CZE) Customer invoice journal (modified form)](https://technet.microsoft.com/en-us/library/jj677569\(v=ax.60\)).

## Related tasks

[(CZE) Create and correct records in the EU sales list](cze-create-and-correct-records-in-the-eu-sales-list.md)

[(CZE) Post a vendor transaction as a correction transaction](cze-post-a-vendor-transaction-as-a-correction-transaction.md)

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
<td><p>Be sure to select the following configuration keys:</p>
<ul>
<li><p><strong>LedgerBasic</strong></p></li>
<li><p><strong>LogisticsBasic</strong></p></li>
<li><p><strong>ProjBasic</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up and create a tax corrective document, you must be a member of a security role that includes the following duties:</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enable invoice and cash process</strong></p></td>
<td><p>CustInvoiceInvoiceAndCashProcessEnable</p></td>
<td><p>Set up a reason code for the tax corrective document.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain general ledger parameters</strong></p></td>
<td><p>LedgerParametersMaintain</p></td>
<td><p>Set up the parameter for cash discounts.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Enable general ledger process</strong></p></td>
<td><p>LedgerGeneralLedgerProcessEnable</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Enable collections process</strong></p></td>
<td><p>CollectionLetterCollectionsProcessEnable</p></td>
<td><p>Set up the parameters for cash discount credit notes.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Enable credit cards</strong></p></td>
<td><p>CreditCardCreditCardEnable</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Enable credit cards process</strong></p></td>
<td><p>CreditCardCreditCardsProcessEnable</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Enable invoice and cash process</strong></p></td>
<td><p>CustInvoiceInvoiceAndCashProcessEnable</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Enable shipping process</strong></p></td>
<td><p>InventShippingProcessEnable</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Enable quotation to sales order process</strong></p></td>
<td><p>SalesQuotationToSalesOrderProcessEnable</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Maintain sales order</strong></p></td>
<td><p>SalesOrderMaintain</p></td>
<td><p>Create and post a credit note for a customer invoice.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain collections transactions</strong></p></td>
<td><p>CollectionLetterCollectionsTransMaintain</p></td>
<td><p>Create and post a credit note for a free text invoice.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain customer invoice transactions</strong></p></td>
<td><p>CustInvoiceCustomerInvoiceTransMaintain</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain project invoices</strong></p></td>
<td><p>ProjProjectInvoiceMaintain</p></td>
<td><p>Create and post a credit note for a project invoice.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain project invoice proposal</strong></p></td>
<td><p>ProjInvoiceProposalMaintain</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Approve posting of service orders</strong></p></td>
<td><p>SMAServiceOrdersJournalize</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Maintain project transactions </strong></p></td>
<td><p>ProjProjectTransactionsMaintain</p></td>
<td></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up and create a tax corrective document, you must be a member of a security role that includes the following privileges:</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain customer reason codes</strong></p></td>
<td><p>CustReasonsMaintain</p></td>
<td><p>Set up a reason code for the tax corrective document.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain general ledger parameters</strong></p></td>
<td><p>LedgerParametersMaintain</p></td>
<td><p>Set up the parameter for cash discounts.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain accounts receivable parameters</strong></p></td>
<td><p>CustParametersMaintain</p></td>
<td><p>Set up the parameters for cash discount credit notes.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain sales order details</strong></p></td>
<td><p>SalesTableDetailsMaintain</p></td>
<td><p>Create and post a credit note for a customer invoice.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain free text invoices</strong></p></td>
<td><p>CustFreeInvoiceMaintain</p></td>
<td><p>Create and post a credit note for a free text invoice.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain invoice proposals</strong></p></td>
<td><p>ProjInvoiceProposalMaintain</p></td>
<td><p>Create and post a credit note for a project invoice.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain all posted project transactions</strong></p></td>
<td><p>ProjPostedProjectTransactionsMaintain</p></td>
<td></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>


## See also

[(CZE) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj838779\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

