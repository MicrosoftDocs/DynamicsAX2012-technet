---
title: (CHN) Export VAT customer invoices or import invoice reference numbers
TOCTitle: (CHN) Export VAT customer invoices or import invoice reference numbers
ms:assetid: 826294d5-b102-4e51-9af2-608fd53b221e
ms:mtpsurl: https://technet.microsoft.com/library/Dn304994(v=AX.60)
ms:contentKeyID: 54900002
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- import
- export
- customer invoices
- China
- CHN
- CN - 00015
- Forms.TaxIntgrExportDocument_CN
- reference numbers
- VAT customer invoices
- MsDynAx060.Forms.TaxIntgrExportDocument_CN
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Export VAT customer invoices or import invoice reference numbers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to export the value-added tax (VAT) customer invoice export documents from Microsoft Dynamics AX, and then import reference numbers for the customer invoices that can be linked to the original invoices.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## This task is part of a bigger process

The following illustration shows how the configuration of the tax integration relates to other tax integration tasks.

For an overview of the process see [(CHN) Chinese tax integration for VAT customer invoices](chn-chinese-tax-integration-for-vat-customer-invoices.md).

![Chinese tax integration for VAT customer invoices](images/Dn304990.ChinaTaxIntegration(AX.60).gif "Chinese tax integration for VAT customer invoices")

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
<td><p>Configure Microsoft Dynamics AX for tax integration. For more information, see <a href="chn-configure-tax-integration.md">(CHN) Configure tax integration</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Make sure that the Application Integration Framework (AIF) batch jobs for the AIFGatewayReceiveService, AIFGatewaySendService, AIFInboundProcessingService, and AIFoutboundProcessingService classes are running. For more information, go to <a href="configuring-batch-jobs-and-tasks-for-aif.md">Configuring batch jobs and tasks for AIF</a> and <a href="walkthrough-exchanging-documents-by-using-the-file-system-adapter.md">Walkthrough: Exchanging documents by using the file system adapter</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related tasks</strong></p></td>
<td><p>Create and post an invoice proposal for a sales invoice. For more information, see <a href="create-and-post-invoice-proposals.md">Create and post invoice proposals</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Create and post a sales order for a customer by using the sales tax group for VAT and the item sales tax group for VAT. For more information, go to <a href="create-or-edit-a-sales-order.md">Create or edit a sales order</a> and <a href="key-tasks-customer-invoices.md">Key tasks: Customer invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Create a credit note by using both the sales tax group for VAT and the item sales tax group for VAT. For more information, go to <a href="about-credit-notes.md">About credit notes</a> and <a href="prepare-a-credit-note.md">Prepare a credit note</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Create and post a free text invoice by using both the sales tax group for VAT and the item sales tax group for VAT. For more information, see <a href="key-tasks-free-text-invoices.md">Key tasks: Free text invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>If the total amount for a VAT customer invoice exceeds the amount that you specify in the <strong>Maximum invoice amount</strong> field in the <strong>Tax integration profiles</strong> form, split the VAT customer invoice. For more information, see <a href="chn-split-or-combine-vat-customer-invoices.md">(CHN) Split or combine VAT customer invoices</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Export VAT customer invoices

Use the **Tax integration export** form to export the VAT customer invoice export documents. You cannot export an invoice that is already exported.

To export VAT customer invoices, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Tax integration** \> **VAT invoice integration**.

2.  Select the invoices to export, and then click **Export** to open the **Tax integration export** form.

3.  In the **Profile** field, select the tax integration profile for the invoice to export.

4.  Select the **Ignore zero amount lines** to exclude the invoice lines that have an amount that is equal to zero.

5.  Click **OK** to export the file.

## 2\. Import VAT customer invoice reference numbers

Use the **Tax integration import** form to import the reference numbers for the VAT customer invoices, which are then linked to the original invoices.

To import VAT customer invoice reference numbers, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Tax integration** \> **VAT invoice integration**.

2.  Click **Import** to open the **Tax integration import** form.

3.  In the **Profile** field, select the identification code for the tax integration profile of the invoice reference number to import.

4.  In the **File folder** field, enter the path and name of the folder to import the files from.

5.  Select the **Import all files in this folder** check box to import all of the files that are available in the folder that you specified in the **File folder** field.

6.  In the **File name** field, enter the path and file name of the file to import.
    

    > [!NOTE]
    > <P>This field is available only if you clear the <STRONG>Import all files in this folder</STRONG> check box.</P>



7.  Click **OK** to import the files.
    
    After you import the files, the **External invoice number** field on the **VAT invoice integration** form is updated with the reference numbers for the corresponding customer invoices.

## Related tasks

[(CHN) Chinese tax integration for VAT customer invoices](chn-chinese-tax-integration-for-vat-customer-invoices.md)

  


