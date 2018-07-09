---
title: (AUT) Generate electronic invoices in PEPPOL format
TOCTitle: (AUT) Generate electronic invoices in PEPPOL format
ms:assetid: c5ec92b9-056d-4a02-845f-918a2188127a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn776173(v=AX.60)
ms:contentKeyID: 62632260
ms.date: 07/30/2014
mtps_version: v=AX.60
f1_keywords:
- eInvoice
- Forms.CustPostInvoiceJob
- Forms.CustFreeInvoiceListPage
- Forms.SalesTableListPage
- Forms.SalesTable
- Forms.CustFreeInvoice
- Forms.ProjInvoiceEditLines
- Forms.SalesEditLines
- Forms.SalesCopying
- Forms.ProjInvoiceProposalListPage
- PEPPOL
---

# (AUT) Generate electronic invoices in PEPPOL format [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic includes information about generating electronic invoices (eInvoices) as XML files by posting sales orders, free text invoices, project invoices, and credit notes, and then converting the eInvoices into the PEPPOL format. The XML files are converted into files in the PEPPOL format during the batch processing of the invoices based on how you have set up AIF, batch groups, and batch jobs to convert the files. For more information about setting up batch processing of eInvoices, see [(AUT) Set up parameters to generate electronic invoices in PEPPOL format](aut-set-up-parameters-to-generate-electronic-invoices-in-peppol-format.md).

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
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up parameters to generate eInvoices in PEPPOL format. For more information, see <a href="aut-set-up-parameters-to-generate-electronic-invoices-in-peppol-format.md">(AUT) Set up parameters to generate electronic invoices in PEPPOL format</a>.</p></li>
<li><p>Create a customer account, and then select the <strong>eInvoice</strong> check box on the <strong>Invoice and delivery</strong> FastTab to use eInvoicing for customer transactions. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa590606(v=ax.60)">Customers (form)</a>.</p></li>
<li><p>Create a funding source that is associated with eInvoice parameters for a project contract in the <strong>Project contracts</strong> form. Select the <strong>Line-specific</strong> check box and enter the dimension account on the <strong>Other</strong> FastTab in the <strong>Funding source details</strong> form. For more information, see <a href="assign-funding-sources-to-a-project-contract.md">Assign funding sources to a project contract</a> and <a href="https://technet.microsoft.com/en-us/library/hh209607(v=ax.60)">Funding source details (form)</a>.</p></li>
<li><p>Create a sales order. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa585863(v=ax.60)">Sales orders (form)</a>.</p></li>
<li><p>Create a free text invoice. For more information, see <a href="key-tasks-free-text-invoices.md">Key tasks: Free text invoices</a> and <a href="https://technet.microsoft.com/en-us/library/aa556897(v=ax.60)">Free text invoice (form)</a>.</p></li>
<li><p>Create a project invoice proposal. For more information, see <a href="create-and-post-invoice-proposals.md">Create and post invoice proposals</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Generate an eInvoice for a sales order

To generate an eInvoice for a sales order, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order with a **Status** of **Open order**, and then click **Edit**.

3.  Click **Header view**, and on the **Setup** FastTab, specify a dimension account for the sales order or select the **Line-specific** check box to specify different dimension accounts for each sales line in **Line view**.

4.  Click **Line view**. On the **Sales order header** FastTab, enter the delivery contact details, customer reference, and customer requisition number.

5.  On the **Line details** FastTab, on the **Setup** tab, enter the dimension account.
    

    > [!NOTE]
    > <P>You can specify a dimension account for a sales line at the line level only if the <STRONG>Line-specific</STRONG> check box is selected in the <STRONG>Header view</STRONG>.</P>



6.  Confirm the sales order. On the **Invoice** tab, click **Invoice**.

7.  Select the **Posting** check box to post the sales order.

8.  Select the **Print invoice** check box to print the sales order invoice when the invoice is posted, and then click **Printer setup** \> **Invoice**.

9.  Click **File**, and then specify the file name and path for the XML file. In the **File format** field, select **XML**.

10. Click **OK** to generate and post the invoice in XML format.

## Generate an eInvoice for a free text invoice

To generate an eInvoice for a free text invoice, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select a free text invoice, and then click **Edit**.

3.  Click **Header view**, and on the **Setup** FastTab, specify a dimension account for the sales order or select the **Line-specific** check box to specify different dimension accounts for each sales line in **Line view**.

4.  On the **Customer** FastTab, enter the customer requisition and customer reference number.

5.  In the **Contact** field, select a contact person.

6.  Click **Line view**. On the **Line details** FastTab, on the **Setup** tab, enter the dimension account.
    

    > [!NOTE]
    > <P>You can specify a dimension account for a sales line at the line level only if the <STRONG>Line-specific</STRONG> check box is selected in the <STRONG>Header view</STRONG>.</P>



7.  On **the Action pane**, click **Post**, and then select the **Posting** check box to post the free text invoice.

8.  Select the **Print invoice** check box to print the free text invoice when the invoice is posted, and then click **Printer setup** \> **Invoice**.

9.  Click **File**, and then specify the file name and path for the XML file. In the **File format** field, select **XML**.

10. Click **OK** to generate and post the free text invoice in the XML format.

## Generate an eInvoice for a project invoice

To generate an eInvoice for a project invoice, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**. Create a project invoice proposal. For more information, see [Create and post invoice proposals](create-and-post-invoice-proposals.md).

2.  On the **Action pane**, click **Post**, and then select the **Posting** check box to post the project invoice.

3.  Select the **Print invoice** check box to print the project invoice when the invoice is posted, and then click **Printer setup**.

4.  Click **File**, and then specify the file name and path for the XML file. In the **File format** field, select **XML**.

5.  Click **OK** to generate and post the free text invoice in XML format.

## Generate an eInvoice for a sales order credit note

To generate an eInvoice for a credit note, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order with a **Status** of **Invoiced**, and then click **Edit**.

3.  On the **Sell** tab, click **Credit note**, and specify the reason code for the sales order transaction.

4.  If required: On the **Invoice** tab, select the **Select all** check box to create a credit note for all of the transactions in the sales order.
    

    > [!NOTE]
    > <P>You can select the <STRONG>Mark</STRONG> check box to create a credit note for a specific transaction in the sales order.</P>



5.  Click **OK**. The details of the selected transaction are updated with the negative amount on the **Sales order lines** FastTab in the **Sales order** form.

6.  Confirm the sales order. On the **Invoice** tab, click **Invoice**.

7.  Select the **Posting** check box to post the sales order.

8.  Select the **Print invoice** check box to print the credit note when the invoice is posted, and then click **Printer setup** \> **Invoice**.

9.  Click **File**, and then specify the file name and path for the XML file. In the **File format** field, select **XML**.

10. Click **OK** to generate and post the credit note in XML format.

## Convert the eInvoices in XML to PEPPOL format

To use a one-time batch job to convert the invoice files from the XML format to the PEPPOL format, follow these steps:

1.  Copy the sales invoice, free text invoice, and credit notes files in the XML format to the source folder (\\\\Server\\PEPPOL\\Sales\\Source).
    
    –or–
    
    Copy the project invoice files in XML format to the source folder (\\\\Server\\PEPPOL\\Project\\Source).

2.  Run the batch job that you set up in [(AUT) Set up parameters to generate electronic invoices in PEPPOL format](aut-set-up-parameters-to-generate-electronic-invoices-in-peppol-format.md) to convert the XML file to the PEPPOL format. You can set up recurring batch jobs to convert the eInvoices to PEPPOL format automatically.

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
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must have the following role:</p>
<ul>
<li><p><strong>Accounts receivable payments clerk</strong></p></li>
</ul>
<p>To generate electronic invoices in PEPPOL format, you must be a member of a security role that includes the following duty:</p>
<ul>
<li><p><strong>Maintain customer payments</strong> (PaymCustomerPaymentsMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

