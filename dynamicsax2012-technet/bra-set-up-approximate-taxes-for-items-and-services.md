---
title: (BRA) Set up approximate taxes for items and services
TOCTitle: (BRA) Set up approximate taxes for items and services
ms:assetid: 745d493e-74cd-4b1b-bc81-8d85f1cedd49
ms:mtpsurl: https://technet.microsoft.com/library/Dn527708(v=AX.60)
ms:contentKeyID: 59626280
author: tonyafehr
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- service
- services
- Forms.EcoResProductDetailsExtended
- Brazil
- Forms.BrazilParameters
- Forms.TaxFiscalClassification_BR
- Forms.ExceptionCode_BR
- approximate tax
- approximate taxes
- imported items
- national item
- BR - 00047
- imported item
- national items
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up approximate taxes for items and services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Approximate taxes are the taxes from production and supply chain that apply to an item. You can specify the approximate tax percentages for national and imported items for each fiscal classification code and exception code. You can specify the approximate tax percentage that is applied to an item or service. You can also specify the source and the text about the approximate tax percentage. When you create and post sales orders or free text invoices, Microsoft Dynamics AX calculates the approximate tax amounts for items by using the approximate tax percentages that you specify.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



When you print a sales fiscal document, the following information for approximate taxes is printed on the fiscal document:

  - The approximate tax amount for each item

  - The total approximate tax amount for all of the items

  - The source and the text for the approximate tax percentage

The information for approximate taxes is printed on the following sales fiscal documents:

  - Fiscal documents that are generated from sales orders

  - Fiscal documents that are generated from free text invoices

  - Nota Fiscal eletrônica (NF-e) documents

  - Documento Auxiliar da Nota Fiscal Eletrônica (DANFE)

  - Fiscal receipts

Follow the steps in this topic to set up approximate tax calculations.

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
<td><p>The primary address for the legal entity must be in the following countries/regions: Brazil</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up fiscal document source texts. For more information, see <a href="bra-set-up-a-fiscal-document-source-text.md">(BRA) Set up a fiscal document source text</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up approximate tax percentages for national and imported items

Use the **Fiscal classification codes** form to set up the approximate tax percentages for national and imported items for a fiscal classification code. Use the **Exception codes** form to set up the approximate tax percentages for national and imported items for an exception code.

To set up approximate tax percentages for national and imported items, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Fiscal information** \> **Fiscal classification codes**.

2.  Select or create a fiscal classification code. For more information, see [(BRA) Fiscal classification codes (form)](https://technet.microsoft.com/library/jj710531\(v=ax.60\)).

3.  In the **Approximate tax percentage for national products** field, enter the tax rate that is used to calculate the approximate tax amount for national items that have a taxation origin of 0 – **National, not related to codes 3 to 5**.

4.  In the **Approximate tax percentage for imported products** field, enter the tax rate that is used to calculate the approximate tax amount for imported items that do not have a taxation origin of 0 – **National, not related to codes 3 to 5**.

5.  Click **Exception code** to open the **Exception codes** form.

6.  Select or create an exception code. For more information, see [(BRA) Exception code (form)](https://technet.microsoft.com/library/jj910969\(v=ax.60\)).

7.  In the **Approximate tax percentage for national products** field, enter the tax rate that is used to calculate the approximate tax amount for national items that have a taxation origin of 0 – **National, not related to codes 3 to 5**.

8.  In the **Approximate tax percentage for imported products** field, enter the tax rate that is used to calculate the approximate tax amount for imported items that do not have a taxation origin of 0 – **National, not related to codes 3 to 5**.

## 2\. Set up approximate tax percentages for items or services

Use the **Released product details** form to set up approximate tax percentages for items or services.

To perform this task, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select or create an item or service, and then on the **Action Pane**, click **Edit**. For more information, see [(BRA) Released product details (modified form)](https://technet.microsoft.com/library/jj923408\(v=ax.60\)), [(BRA) Set up taxation origin for items](bra-set-up-taxation-origin-for-items.md), and [(BRA) Set up fiscal information](bra-set-up-fiscal-information.md).

3.  On the **Fiscal information** FastTab, in the **Approximate tax percentage** field, enter the tax rate that is used to calculate the approximate tax amount for the item or service.

4.  Repeat steps 2 and 3 to set up approximate tax percentages for additional items or services.

## 3\. Set up the source and text for approximate tax percentages

Use the **Brazilian parameters** form to set up the source and text for the approximate tax percentage.

To perform this task, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Brazilian parameters**.

2.  Click **Fiscal document**, and then in the **Fiscal document** area, in the **Approximate taxes** field group, in the **Source** field, enter the source of the approximate tax percentage that is printed on the fiscal documents.

3.  In the **Approximate taxes** field group, in the **Text ID** field, select the fiscal document source text for the approximate tax that is printed on fiscal documents.

4.  Select the **Final user** check box to indicate that the text for the approximate tax is printed only on sales documents that are issued for sales to final users.

## Next step

You have finished setting up approximate tax calculations. Continue to create and post sales orders and free text invoices using the fiscal classification codes, exception codes, items, or services that you set up. For more information about how to create and post a sales order or a free text invoice, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md) and [(BRA) Create and post a free text invoice](bra-create-and-post-a-free-text-invoice.md).

## Related tasks

[(BRA) Set up Brazilian parameters](bra-set-up-brazilian-parameters.md)

[(BRA) Brazilian parameters (form)](https://technet.microsoft.com/library/jj822920\(v=ax.60\))

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
</tbody>
</table>

  


