---
title: Create and upload EU entry certificates for customer invoices
TOCTitle: Create and upload EU entry certificates for customer invoices
ms:assetid: 851192e2-e34c-45a2-98c5-f18c088c3cef
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn781484(v=AX.60)
ms:contentKeyID: 62807572
ms.date: 08/20/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustInvoiceJournal
- packing slip
- Forms.LedgerJournalTable
- Forms.SalesEditLines
- Customer invoice
- entry certificate
- EU entry certificate
- Forms.CustEntryCertificateJour_W
audience: Application User
ms.search.region: Global
---

# Create and upload EU entry certificates for customer invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create and upload a European Union (EU) entry certificate. You can complete the following tasks for an EU entry certificate:

  - Create and issue an EU entry certificate along with a packing slip or customer invoice for the delivery of items or services to EU countries.

  - Receive the EU entry certificate that is signed by an EU customer.

  - Upload the signed EU entry certificate that is received from the customer or from a third-party who is responsible for delivering items to the customer.

  - Associate the uploaded EU entry certificate with a customer invoice.

  - Update the status of the uploaded EU entry certificate.

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
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later. This feature is also available for Microsoft Dynamics AX 2009 SP1 as a hotfix.</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: EU member state</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related set up tasks</strong></p></td>
<td><ul>
<li><p>Select the <strong>Enable entry certificate management</strong> and <strong>Enable entry certificate issuing</strong> check boxes in the <strong>Accounts receivable parameters</strong> form.</p></li>
<li><p>In the <strong>Customers</strong> form, on the <strong>Invoice and delivery</strong> FastTab, select the <strong>Entry certificate required</strong> check box to indicate that an EU entry certificate is mandatory for the customer. Select the <strong>Issue entry certificate</strong> check box to issue an EU entry certificate of the legal entity to the customer.</p></li>
<li><p>Select a number sequence code for the <strong>Entry certificate</strong> reference in the <strong>Accounts receivable parameters</strong> form.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Related transactions</strong></p></td>
<td><ul>
<li><p>Create a customer account. For more information, see <a href="create-a-customer-record.md">Create a customer record</a>.</p></li>
<li><p>Create a sales order. For more information, see <a href="create-or-edit-a-sales-order.md">Create or edit a sales order</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Create an EU entry certificate

You can create an EU entry certificate automatically or manually. An EU entry certificate is created and printed automatically when you post a packing slip or invoice for a customer using the **Packing slip posting** form or the **Posting invoice** form. You can create an EU entry certificate manually for a customer invoice using the **Invoice journal** form and reprint the EU entry certificate. Additionally, you can enter details about an EU entry certificate that is issued by a third-party using the **Entry certificate journal** form.

## Create an EU entry certificate automatically using a packing slip or an invoice

To create an EU entry certificate using a packing slip, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click the sales order that you want to create an EU entry certificate for, and then click **Edit**.
    

    > [!NOTE]
    > <P>On the <STRONG>Setup</STRONG> FastTab, in the <STRONG>Entry certificate</STRONG> field group, if the <STRONG>Entry certificate required</STRONG> check box is selected, it indicates that entry certificates are mandatory for the selected sales order. If the <STRONG>Issue entry certificate</STRONG> check box is selected, it indicates that an EU entry certificate for the legal entity or third-party is issued.</P>



3.  In the **Sales order** form, on the **Pick and pack** tab, click **Packing slip**.

4.  In the **Packing slip posting** form, in the **Quantity** field, select **Packing slip**.

5.  Select the **Print entry certificate** check box to print the EU entry certificate while posting the packing slip.
    

    > [!NOTE]
    > <P>The <STRONG>Issue entry certificate</STRONG> check box is selected automatically if you selected this check box in the <STRONG>Customers</STRONG> form.</P>



6.  Click **OK** to post the packing slip and print the EU entry certificate.

–or–

To create an EU entry certificate using an invoice, follow these steps:

1.  In the **Sales order** form, on the **Invoice** tab, click **Invoice**.

2.  In the **Posting invoice** form, select the **Print entry certificate** check box to print the EU entry certificate while posting the invoice.
    

    > [!NOTE]
    > <P>The <STRONG>Entry certificate required</STRONG> and <STRONG>Issue entry certificate</STRONG> check boxes are selected automatically if you selected these check boxes in the <STRONG>Customers</STRONG> form.</P>



3.  Click **OK** to post the invoice and print the EU entry certificate.

## Create an EU entry certificate manually using the Invoice journal form

You must change the certification status of an invoice before manually creating an EU entry certificate.

To create an EU entry certificate using the **Invoice journal** form, follow these steps:

1.  In the **Sales order** form, on the **Invoice** tab, in the **Journals** group, click **Invoice** to open the **Invoice journal** form.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  On the **Overview** tab, select a customer invoice that you want to create an EU entry certificate for, and then click **Entry certificate** \> **Change entry certification status**.

3.  In the **New status** field, select **Required**, and then click **OK**.

4.  Click **Entry certificate** \> **Create entry certificate** to open the **Create entry certificate** form.

5.  Click **OK** to create an EU entry certificate for the customer invoice.

## If required: Register details of an EU entry certificate that is issued by a third party

To register details of an EU entry certificate that is issued by a third party, follow these steps:

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Entry certificate journal**.

2.  Click **New** to create an EU entry certificate journal line. The **Third-party certificate** check box is selected automatically.

3.  Specify the EU entry certificate number and the customer account number.
    

    > [!NOTE]
    > <P>The default status of the EU entry certificate is <STRONG>Not printed</STRONG>.</P>



## Upload a received EU entry certificate that is signed by the customers

Use the **Document handling of %1** form to upload a received EU entry certificate that is signed by an EU customer. After the certificate is uploaded, you can associate the EU entry certificate with an invoice as proof of the delivery of items. This proof is necessary to issue an invoice without VAT and is used during auditing.

To upload an EU entry certificate, follow these steps:

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Entry certificate journal**.

2.  On the **Overview** tab, select an EU entry certificate journal line that you want to upload a signed EU entry certificate for.

3.  Click **File** \> **Command** \> **Document handling** to open the **Document handling of %1** form, and then upload the signed EU entry certificate document. For more information, see [Create a reference to an existing document](create-a-reference-to-an-existing-document.md).
    

    > [!NOTE]
    > <P>After the document is uploaded, the <STRONG>Entry certificate documents attached</STRONG> check box is selected for the EU entry certificate journal line in the <STRONG>Entry certificate journal</STRONG> form, and the <STRONG>Entry certificate receipt status</STRONG> field is updated to <STRONG>Received</STRONG> in the <STRONG>Invoice journal</STRONG> form.</P>



4.  Select the uploaded EU entry certificate, and then in the **Associated invoices** pane, click **Add**.

5.  In the **Invoice** field, select the invoice that is related to the entry certificate.

## Optional: Update the certification status of an invoice and the printing status of an EU entry certificate

To update the entry certification status of a customer invoice, follow these steps:

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  Select a customer invoice, and then click **Entry certificate** \> **Change entry certification status**.

3.  In the **New status** field, select **Not required**, **Required**, or **Received**.

To update the printing status of an EU entry certificate, follow these steps:

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Entry certificate journal**.

2.  On the **Overview** tab, select an EU entry certificate that you want to change the printing status for.

3.  Click **Change status**, and then in the **New status** field, select **Cancelled**, **Printed**, or **Not printed**.

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
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up and create EU entry certificates for items or services, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Accounts receivable clerk</strong> (CustInvoiceAccountsReceivableClerk)</p></li>
<li><p><strong>Customer service representative</strong> (TradeCustomerServiceRepresentative)</p></li>
<li><p><strong>Sales clerk</strong> (TradeSalesClerk)</p></li>
<li><p><strong>Shipping clerk</strong> (InventShippingClerk)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


