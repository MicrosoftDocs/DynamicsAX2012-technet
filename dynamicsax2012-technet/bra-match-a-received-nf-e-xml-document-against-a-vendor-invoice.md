---
title: (BRA) Match a received NF-e XML document against a vendor invoice
TOCTitle: (BRA) Match a received NF-e XML document against a vendor invoice
ms:assetid: 9e48008f-a3f7-4884-bd19-78edfebc48f9
ms:mtpsurl: https://technet.microsoft.com/library/Dn753711(v=AX.60)
ms:contentKeyID: 62485055
author: Khairunj
ms.date: 06/09/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.VendFiscalDocumentType_BR
- NF-e
- Forms.FiscalEstablishment_BR
- divergence
- Forms.FiscalEstablishmentFiscalDocumentType_BR
- Forms.VendInvoiceXmlMapping_BR
- Forms.VendInvoiceXmlMatch_BR
- Forms.VendInvoiceXmlMatchApproval_BR
- Match NF-e XML document
audience: Application User
ms.search.region: Brazil
---

# (BRA) Match a received NF-e XML document against a vendor invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Follow the steps in this topic to automatically match a vendor’s Cadastro Nacional da Pessoa Jurídica (CNPJ) and Inscrição Estadual (IE) and the total amounts in the received Nota Fiscal electronica (NF-e) XML document against a vendor invoice. If you select the **Block NF-e posting if XML does not match** check box on the **NF-e federal** FastTab in the **Fiscal establishments** form, you can post only the electronic fiscal documents for which the XML document information matches the vendor invoice information.

If there are divergences between the received XML document information and the vendor invoice information for the following values, you can approve the divergences to post the vendor invoice:

  - Total fiscal document amount

  - Total product amount

  - Total freight amount

  - Total other charges

  - Total Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) base amount

  - Total ICMS-ST (ICMS tributary substitution) base amount

  - Total ICMS-ST amount

  - Total Imposto Sobre Produtos Industrializados (IPI) amount

If you have approved the divergences once and the divergences change, you can cancel the earlier approval and request a new approval.

If there are divergences in the vendor’s CNPJ and IE, these divergences cannot be approved, and the vendor invoice cannot be posted.

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
<td><p>Microsoft Dynamics AX 2012 R3</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Brazil</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up a fiscal establishment group. For more information, see <a href="bra-create-a-fiscal-establishment-group.md">(BRA) Create a fiscal establishment group</a>.</p></li>
<li><p>Set up a fiscal establishment, and then set up the NF-e parameters for the fiscal establishment. For more information, see <a href="bra-create-a-fiscal-establishment.md">(BRA) Create a fiscal establishment</a>, <a href="https://technet.microsoft.com/library/jj933531(v=ax.60)">(BRA) Fiscal establishments (form)</a>, and <a href="bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md">(BRA) Set up NF-e parameters for a fiscal establishment</a>.</p></li>
<li><p>Set up email accounts to import XML files and to import the NF-e XML files from emails. For more information, see <a href="bra-set-up-import-and-verify-nf-e-xml-documents-and-danfe-that-you-receive-in-emails.md">(BRA) Set up, import, and verify NF-e XML documents and DANFE that you receive in emails</a> and <a href="bra-import-and-verify-nf-e-xml-documents-and-danfe-that-you-receive-in-emails.md">(BRA) Import and verify NF-e XML documents and DANFE that you receive in emails</a>.</p></li>
<li><p>Set up external item descriptions to allow the mapping of the vendor item code that is received in the NF-e XML to the item that is used in the vendor invoice. For more information, see <a href="modify-the-external-item-description.md">Modify the external item description</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Verify the vendor invoice information and the received NF-e XML information, and then approve divergences

Use this procedure to verify the vendor invoice information and the received NF-e XML information. If there are divergences for the total amounts in the fiscal documents, you can verify the divergences, and then approve or request approval for the divergences.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select an approved purchase order for which the NF-e XML document is received. For more information, see [Create vendor invoices from purchase orders](create-vendor-invoices-from-purchase-orders.md) and [(BRA) Enter vendor invoice lines to a vendor invoice for a purchase order](bra-enter-vendor-invoice-lines-to-a-vendor-invoice-for-a-purchase-order.md).

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  In the **Document model** field, select the fiscal document model.

5.  In the **Vendor invoice** form, in the **Access key** field, enter the identification code of the access key for the vendor invoice.

6.  On the **Action Pane**, click **NF-e XML matching details** to open the **View the NF-e XML and vendor invoice matching details** form, and then verify the details of the vendor invoice and the received NF-e XML document.
    

    > [!NOTE]
    > <P>The <STRONG>NF-e XML matching details</STRONG> button is available only if you enter an access key in the <STRONG>Access key</STRONG> field.</P>

    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Approval status</strong></p></td>
    <td><p>The approval status of the divergences, if any.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Invoice</strong></p></td>
    <td><p>The number of the vendor invoice.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Access key</strong></p></td>
    <td><p>The access key of the NF-e.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>CNPJ</strong></p></td>
    <td><p>The CNPJ of the vendor in the vendor invoice and the NF-e XML document.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>IE</strong></p></td>
    <td><p>The IE of the vendor in the vendor invoice and the NF-e XML document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount</strong></p></td>
    <td><p>The amount of the vendor invoice and the NF-e XML document.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Total products amount</strong></p></td>
    <td><p>The total amount of the vendor invoice items and the NF-e XML document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Freight</strong></p></td>
    <td><p>The vendor invoice freight charges and the NF-e XML document.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Insurance</strong></p></td>
    <td><p>The vendor invoice insurance charges and the NF-e XML document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Other charges</strong></p></td>
    <td><p>The other vendor invoice charges and the NF-e XML document.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>IPI</strong></p></td>
    <td><p>The vendor invoice IPI tax amount and the NF-e XML document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ICMS base amount</strong></p></td>
    <td><p>The base amount on which the ICMS tax is calculated for the vendor invoice and the NF-e XML document.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ICMS</strong></p></td>
    <td><p>The vendor invoice ICMS tax amount and the NF-e XML document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ICMS-ST base amount</strong></p></td>
    <td><p>The base amount on which the ICMS-ST tax is calculated for the vendor invoice and the NF-e XML document.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ICMS-ST</strong></p></td>
    <td><p>The vendor invoice ICMS-ST tax amount and the NF-e XML document.</p></td>
    </tr>
    </tbody>
    </table>


7.  To approve divergences, click **Approve divergences**, and then in the **Reason** field, enter the reason to approve the divergences. Click **OK**.
    
    –or–
    
    If you have approved the divergences once and the divergences change, click **Requires new approval** to cancel the previous approval and request a new approval. You can then click **Approve divergences** again to approve the divergences.

You can view the approved divergences in the **Approved divergences** form.

## View the XML document for the received NF-e

Use this procedure to view the XML document for the received NF-e.

You can view the totals for product amounts, discounts, freight amounts, insurance amounts, other charges, ICMS base amounts, ICMS amounts, ICMS-ST base amounts, ICMS-ST, IPI, fiscal document amounts, and the issue date of the NF-e in both the header and line view of the received XML document.

In the line view of the received XML document, you can view information that is related to the NF-e lines, such as the item code, description, quantity, unit, unit price, CFOP code, fiscal classification code, discount, FCI number, ICMS value, IPI value, IPI base amount, IPI amount, ICMS ST, freight charges, insurance changes, other charges, and addition information about the XML.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select an approved purchase order for which the NF-e XML document is received.

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  In the **Document model** field, select the fiscal document model.

5.  In the **Vendor invoice** form, in the **Access key** field, enter the identification code of the access key for the vendor invoice.

6.  On the **Action Pane**, click **XML document** to view the XML document for the received NF-e.

## Verify the mapping between the received NF-e XML document and the vendor invoice

Use this procedure to verify the mapping between the received NF-e XML document and the vendor invoice. The mapping is done based on external item descriptions.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select an approved purchase order for which the NF-e XML document is received.

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  In the **Document model** field, select the fiscal document model.

5.  In the **Vendor invoice** form, in the **Access key** field, enter the identification code of the access key for the vendor invoice.

6.  On the **Action Pane**, click **NF-e XML mapping details** to open the **View mapping** form, and then verify the quantity and price information for the received NF-e XML document and the vendor invoice.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Access key</strong></p></td>
    <td><p>The access key of the NF-e document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Purchase order</strong></p></td>
    <td><p>The purchase order number.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the vendor.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Vendor invoice item code</strong></p></td>
    <td><p>The item number on the vendor invoice line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Vendor invoice item code</strong></p></td>
    <td><p>The number of the vendor invoice line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Vendor invoice unit price</strong></p></td>
    <td><p>The unit price of the item on the vendor invoice line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Vendor invoice quantity</strong></p></td>
    <td><p>The quantity of the item of the vendor invoice line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Mapping status</strong></p></td>
    <td><p>The status of the mapping.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>NF-e XML item code</strong></p></td>
    <td><p>The item number on the NF-e XML document line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>NF-e XML line number</strong></p></td>
    <td><p>The number of the NF-e XML document line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>NF-e XML unit price</strong></p></td>
    <td><p>The unit price of the item on the NF-e XML document line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>NF-e XML quantity</strong></p></td>
    <td><p>The quantity of the item on the NF-e XML document line.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Vendor invoice taxation origin</strong></p></td>
    <td><p>The taxation origin of the vendor invoice line.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Vendor invoice fiscal classification code</strong></p></td>
    <td><p>The fiscal classification code of the vendor invoice.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>NF-e XML taxation origin</strong></p></td>
    <td><p>The taxation origin of the NF-e XML document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>NF-e XML fiscal classification code</strong></p></td>
    <td><p>The fiscal classification code of the NF-e XML document.</p></td>
    </tr>
    </tbody>
    </table>


## Update the quantity and unit price from the received NF-e XML document on the vendor invoice

Use this procedure to update the quantity, unit price, and discount in the vendor invoice lines using the information from the received NF-e XML document lines that are mapped.


> [!NOTE]
> <P>The discount in the vendor invoice line is for a unit, whereas the discount in the NF-e XML line is the total for a line. The discount for a unit of the item is recalculated when you update the discount rate.</P>



To perform this task, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select an approved purchase order for which the NF-e XML document is received.

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  In the **Document model** field, select the fiscal document model.

5.  Click **Update from NF-e XML**, and then click **Yes** to update the quantities, unit prices, and discounts of the vendor invoice lines using the values from the received NF-e XML lines.

## Related tasks

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

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
<td><p>To perform this task, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p>Match a vendor invoice to an NF-e XML document</p></li>
<li><p>View the discrepancies between vendor invoice values and received NF-e XML values</p></li>
<li><p>Maintain vendor invoices</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p>View the discrepancies between vendor invoice values and the received XML values</p></li>
<li><p>View approved divergences</p></li>
<li><p>Request new approval</p></li>
<li><p>View the mapping between vendor invoice lines and NF-e XML lines</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


