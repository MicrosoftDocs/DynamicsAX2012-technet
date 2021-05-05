---
title: About Accounts payable invoice matching
TOCTitle: About Accounts payable invoice matching
ms:assetid: caaf1767-e6d6-4fbf-9bd7-3e4f0bd3b6d9
ms:mtpsurl: https://technet.microsoft.com/library/Hh242852(v=AX.60)
ms:contentKeyID: 36059334
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accounts
- AP
- payable
- matching
- 2 way
- 3 way
- 2-way
- discrepancies
- 3-way
- two way
- PO invoice matching
- discrepancy
- invoice matching
- three-way
- totals matching
- three way
- purchase order invoice matching
- two-way
- vendor invoice matching
audience: Application User
ms.search.region: Global
---

# About Accounts payable invoice matching 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Accounts payable invoice matching is the process of matching vendor invoice, purchase order, and product receipt information. Differences among these documents are called matching discrepancies. Matching discrepancies are compared with the tolerances that are specified. If a matching discrepancy exceeds the tolerance percentage or amount, match variance icons are displayed in the **Vendor invoice** form and in the **Invoice matching details** form.

For example, you enter a purchase order with one line item for 1,000 batteries at a price of 1.00 each. The purchase order is approved and submitted to the vendor. The vendor ships 1,000 batteries, and you enter a product receipt for 1,000 batteries at a price of 1.00 each. The inventory cost for the batteries is updated with this price.

An invoice arrives for 1,000 batteries at a price of 1.10 each. Your legal entity policy allows a 5 percent net unit price tolerance for this category of item. A price of 1.05 would be acceptable, but 1.10 is not. When you enter the invoice information, a price matching discrepancy is identified and you can save the invoice until the discrepancy is resolved.

You can use the following types of Accounts payable invoice matching:

  - Invoice totals matching – Match the total amounts on the invoice to the total amounts on the purchase order. This type of invoice matching includes the least amount of detail, so you can use this option to set up controls that minimize the staff time that is required to review invoice matching information.

  - Two-way matching – Match the price information on the invoice to the price information on the purchase order.

  - Three-way matching – Match the price information on the invoice to the price information on the purchase order. Also match the quantity information on the invoice to the quantity information on the product receipts that are selected for the invoice.

  - Charges matching – Match the charges information (amounts) on the invoice to the charges information (amounts) on the purchase order.


> [!NOTE]
> <P>Other forms of invoice validation can be done using vendor invoice policies.</P>



Two-way matching and three-way matching always match price information by the unit price. You can also configure these matching policies to match price information by the price total.

  - Net unit price matching – Match price information for two-way matching or three-way matching by comparing the net unit price for each line on the invoice with the corresponding net unit price on the purchase order. The net unit price is determined by the following formula: Net amount of the line / Quantity of the line

  - Price totals matching – Match price information for two-way matching or three-way matching by comparing the net amount (price total) for each line on the invoice with the corresponding net amount on the purchase order. The net amount is determined by the following formula: (Unit price \* Line quantity) + Line charges - Line discounts

Typically, invoice matching calculations are automatically performed when you edit vendor invoices in the **Vendor invoice** form. Invoice matching can also be performed as part of an invoice review process. You can view the results of automatic invoice matching in the **Vendor invoice** form and related invoice matching forms.

## Invoice totals matching

You can use invoice totals matching to help make sure that total invoice amounts do not deviate from expected amounts by more than an acceptable variance. Six totals are compared in the **Invoice totals matching details** form, as shown in the following table. If the allowable tolerance for invoice totals matching is 20%, the 100% variance percentage for the total discount amount is considered a matching discrepancy.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Total field</p></th>
<th><p>Actual invoice total</p></th>
<th><p>Expected invoice total</p></th>
<th><p>Variance percentage</p></th>
<th><p><strong>Match variance</strong> icon</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Balance</strong></p></td>
<td><p>495.00</p></td>
<td><p>495.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Total discount</strong></p></td>
<td><p>0.00</p></td>
<td><p>9.90</p></td>
<td><p>100%</p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
<tr class="odd">
<td><p><strong>Charges</strong></p></td>
<td><p>64.90</p></td>
<td><p>64.90</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Sales tax</strong></p></td>
<td><p>139.98</p></td>
<td><p>137.50</p></td>
<td><p>2%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p><strong>Round-off</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Invoice amount</strong></p></td>
<td><p>699.88</p></td>
<td><p>687.50</p></td>
<td><p>2%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
</tbody>
</table>


Invoice totals matching is controlled for the legal entity by the **Match invoice totals** check box in the **Accounts payable parameters** form. Matching is performed on the expected invoice totals and the actual invoice totals. The expected invoice totals are calculated based on the prices, charges, and sales tax information from the purchase order and the quantities from the invoice.

## Two-way, price totals matching

Use two-way matching to help make sure that the variance between the price information on the purchase order and the invoice is within acceptable tolerances. You can compare price information for the net amount of each line on the invoice, and all pending and previously posted invoice lines, with the net amount of the corresponding purchase order line. This is called price totals matching.

Price totals matching can be based on a percentage, an amount, or a percentage and amount.

If a purchase price total tolerance percentage is specified, five fields are compared, as shown in the following table. Because the purchase price total tolerance percentage is 10%, the price total variance percentage of 50% represents a matching discrepancy.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Match variance</strong> icon</p></th>
<th><p><strong>Invoice net amount</strong></p></th>
<th><p><strong>Expected net amount</strong></p></th>
<th><p><strong>Unmatched purchase price total</strong> (variance amount)</p></th>
<th><p><strong>Unmatched purchase price total percentage</strong> (variance percentage)</p></th>
<th><p><strong>Purchase price total tolerance percent</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><p>105.00</p></td>
<td><p>100.00</p></td>
<td><p>5.00</p></td>
<td><p>5%</p></td>
<td><p>10%</p></td>
</tr>
<tr class="even">
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><p>150.00</p></td>
<td><p>100.00</p></td>
<td><p>50.00</p></td>
<td><p>50%</p></td>
<td><p>10%</p></td>
</tr>
</tbody>
</table>


If a purchase price total tolerance amount is specified, five fields are compared, as shown in the following table. Because the purchase price total tolerance amount is 100.00, the price total variance amount of 105.00 represents a matching discrepancy.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Match variance</strong> icon</p></th>
<th><p><strong>Invoice net amount</strong></p></th>
<th><p><strong>Expected net amount</strong></p></th>
<th><p><strong>Unmatched purchase price total</strong> (variance amount)</p></th>
<th><p><strong>Unmatched purchase price total in accounting currency</strong> (variance amount)</p></th>
<th><p><strong>Purchase price total tolerance</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><p>150.00</p></td>
<td><p>100.00</p></td>
<td><p>50.00</p></td>
<td><p>50.00</p></td>
<td><p>100.00</p></td>
</tr>
<tr class="even">
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><p>205.00</p></td>
<td><p>100.00</p></td>
<td><p>105.00</p></td>
<td><p>105.00</p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


If price totals matching is set up with a percentage tolerance and a tolerance amount, sometimes referred to as a not-to-exceed amount, both tolerances are considered when evaluating whether a line has a matching discrepancy. If either the percentage or the amount exceeds the tolerance, as shown in the 150.00 and 205.00 lines in the following table, the line has a matching discrepancy.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Match variance</strong> icon</p></th>
<th><p><strong>Invoice net amount</strong></p></th>
<th><p><strong>Expected net amount</strong></p></th>
<th><p><strong>Unmatched purchase price total percentage</strong> (variance percentage)</p></th>
<th><p><strong>Purchase price total tolerance percent</strong></p></th>
<th><p><strong>Unmatched purchase price total in accounting currency</strong> (variance amount)</p></th>
<th><p><strong>Purchase price total tolerance</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><p>105.00</p></td>
<td><p>100.00</p></td>
<td><p>5%</p></td>
<td><p>10%</p></td>
<td><p>5.00</p></td>
<td><p>100.00</p></td>
</tr>
<tr class="even">
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><p>150.00</p></td>
<td><p>100.00</p></td>
<td><p>50%</p></td>
<td><p>10%</p></td>
<td><p>50.00</p></td>
<td><p>100.00</p></td>
</tr>
<tr class="odd">
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><p>205.00</p></td>
<td><p>100.00</p></td>
<td><p>105%</p></td>
<td><p>10%</p></td>
<td><p>105.00</p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


Two-way matching is controlled for the legal entity by the **Line matching policy** field in the **Accounts payable parameters** form. Depending on the selection in the **Allow matching policy override** field, you can select two-way matching for a specific vendor, item, or item and vendor combination in the **Matching policy** form, and for a specific purchase order in the **Purchase order** form.

Price totals matching is controlled for the legal entity by the **Match price totals** field in the **Accounts payable parameters** form. The purchase price total tolerance percentage and tolerance amount (not-to-exceed amount) are also specified in that form.

## Two-way, net unit price matching

Use two-way matching to help make sure that the variance between the price information on the purchase order and the invoice is within acceptable tolerances. You can compare price information for the net unit price of each item on the invoice. This is called net unit price matching.

Nine line amounts are compared in the **Invoice matching details** form, as shown in the following table. If the allowable price tolerance for net unit price matching is 10%, the 22.61% variance for the net unit price is considered a matching discrepancy.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Line field</p></th>
<th><p><strong>Invoice</strong> value</p></th>
<th><p><strong>Purchase order</strong> value</p></th>
<th><p>Variance percentage</p></th>
<th><p>Matching icon</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Unit price</strong></p></td>
<td><p>55.40</p></td>
<td><p>55.38</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Price unit</strong></p></td>
<td><p>1.00</p></td>
<td><p>1.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p><strong>Charges on purchases</strong></p></td>
<td><p>50.00</p></td>
<td><p>0.00</p></td>
<td><p>100%</p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
<tr class="even">
<td><p><strong>Discount</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p><strong>Discount percent</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Multiline discount</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p><strong>Multiline discount percentage</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Net amount</strong></p></td>
<td><p>271.60</p></td>
<td><p>221.52</p></td>
<td><p>22.61%</p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
<tr class="odd">
<td><p><strong>Net unit price</strong></p></td>
<td><p>67.9000</p></td>
<td><p>55.3800</p></td>
<td><p>22.61%</p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
</tbody>
</table>


Two-way matching is controlled for the legal entity by the **Line matching policy** field in the **Accounts payable parameters** form. Depending on the selection in the **Allow matching policy override** field, you can select two-way matching for a specific vendor, item, or item and vendor combination in the **Matching policy** form, and for a specific purchase order in the **Purchase order** form.

Net unit price matching is controlled for the legal entity by the **Enable invoice matching validation** field in the **Accounts payable parameters** form. The net unit price tolerance percentages can be configured for items, item groups, vendors, vendor groups, item and vendor combinations, or legal entity by using the **Price tolerances** form.

## Two-way, price totals matching and net unit price matching

You can use price totals matching and net unit price matching together. This example assumes the following configuration:

  - The net unit price tolerance for the USB Drive item is 10%.

  - The price totals matching tolerance for the legal entity is 15% or 500.00.

The purchase order contains the following line.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Item number</strong></p></th>
<th><p><strong>Quantity</strong></p></th>
<th><p><strong>Unit price</strong></p></th>
<th><p><strong>Net amount</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>USB Drive</p></td>
<td><p>1,000</p></td>
<td><p>10.00</p></td>
<td><p>10,000.00</p></td>
</tr>
</tbody>
</table>


Three invoices are entered, as shown in the following table. There is an invoice matching discrepancy for Invoice 3 because the variance of 1,880.00 exceeds the purchase price total tolerance amount of 500.00. For price totals matching, the invoice net amount includes all previously posted invoices in addition to the invoice that you are currently working with.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Item number</strong></p></th>
<th><p><strong>Quantity</strong></p></th>
<th><p><strong>Unit price</strong></p></th>
<th><p><strong>Net amount</strong></p></th>
<th><p><strong>Price match</strong> icon</p></th>
<th><p><strong>Price total match</strong> icon</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoice 1: USB Drive</p></td>
<td><p>800</p></td>
<td><p>10.80</p></td>
<td><p>8,640.00</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p>Invoice 2: USB Drive</p></td>
<td><p>100</p></td>
<td><p>10.80</p></td>
<td><p>1,080.00</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p>Invoice 3: USB Drive</p></td>
<td><p>200</p></td>
<td><p>10.80</p></td>
<td><p>2,160.00</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
<tr class="even">
<td><p>Total</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>11,880.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Three-way matching

Use three-way matching to help make sure that the variance between the price information on the purchase order and the invoice is within acceptable tolerances, and to make sure that the quantity on the invoice matches the quantity on the corresponding product receipts.

The same line amounts are compared in the **Invoice matching details** form as for two-way matching. In addition, the quantity on the invoice is matched to product receipt quantities that have been received. If the invoice quantity differs from the matched product receipt quantity, a quantity matching error exists.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Line field</p></th>
<th><p><strong>Invoice</strong> value</p></th>
<th><p><strong>Purchase order</strong> value</p></th>
<th><p>Variance percentage</p></th>
<th><p>Matching icon</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Unit price</strong></p></td>
<td><p>55.40</p></td>
<td><p>55.38</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Price unit</strong></p></td>
<td><p>1.00</p></td>
<td><p>1.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p><strong>Charges on purchases</strong></p></td>
<td><p>50.00</p></td>
<td><p>0.00</p></td>
<td><p>100%</p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
<tr class="even">
<td><p><strong>Discount</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p><strong>Discount percent</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Multiline discount</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p><strong>Multiline discount percentage</strong></p></td>
<td><p>0.00</p></td>
<td><p>0.00</p></td>
<td><p>0%</p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p><strong>Net amount</strong></p></td>
<td><p>271.60</p></td>
<td><p>221.52</p></td>
<td><p>22.61%</p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
<tr class="odd">
<td><p><strong>Net unit price</strong></p></td>
<td><p>67.9000</p></td>
<td><p>55.3800</p></td>
<td><p>22.61%</p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Line field</p></th>
<th><p><strong>Invoice</strong> value</p></th>
<th><p>Matching icon</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Invoice quantity</strong></p></td>
<td><p>4.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Total product receipts matched</strong></p></td>
<td><p>0.00</p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
</tr>
</tbody>
</table>


Three-way matching is controlled for the legal entity by the **Line matching policy** field in the **Accounts payable parameters** form. Depending on the selection in the **Allow matching policy override** field, you can select three-way matching for a specific vendor, item, or item and vendor combination in the **Matching policy** form, and for a specific purchase order in the **Purchase order** form.

## Charges matching

You can use charges matching to help make sure that charges amounts do not deviate from expected amounts by more than an acceptable variance percentage. The total amounts for each charges code that applies to the invoice and purchase order are compared in the **Compare charges values - Invoice: %1** form, as shown in the following table. If the allowable tolerance for the charges code is 25%, the 99,999,999,999.99% variance percentage for the License charges code is considered a matching discrepancy.


> [!NOTE]
> <P>A variance percentage of 99,999,999,999.99% means that the expected amount based on the purchase order is zero and the actual amount on the invoice is a positive value.</P>



<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Charges match</strong> icon</p></th>
<th><p><strong>Invoice charges code</strong></p></th>
<th><p><strong>Actual total calculated value</strong></p></th>
<th><p><strong>Expected total calculated value</strong></p></th>
<th><p><strong>Variance amount</strong></p></th>
<th><p><strong>Variance percentage</strong></p></th>
<th><p><strong>Tolerance percentage</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><p>License</p></td>
<td><p>25</p></td>
<td><p>0</p></td>
<td><p>25</p></td>
<td><p>99,999,999,999.99%</p></td>
<td><p>25%</p></td>
</tr>
<tr class="even">
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><p>Freight</p></td>
<td><p>200</p></td>
<td><p>200</p></td>
<td><p>0</p></td>
<td><p>0%</p></td>
<td><p>25%</p></td>
</tr>
<tr class="odd">
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><p>Expedite</p></td>
<td><p>4</p></td>
<td><p>2</p></td>
<td><p>2</p></td>
<td><p>100%</p></td>
<td><p>25%</p></td>
</tr>
</tbody>
</table>


Charges matching is controlled for the legal entity by the **Match charges** check box in the **Accounts payable parameters** form. You can set up variance tolerance percentages for charges in the **Charges tolerances** form.


> [!NOTE]
> <P>Charges matching is performed only on charges codes for which the <STRONG>Compare purchase order and invoice values</STRONG> check box is selected in the <STRONG>Charges code</STRONG> form.</P>



## Related functionality

Vendor invoices are often based on product receipts that represent actual shipments, instead of on purchase orders. Sometimes the invoiced amounts do not match the purchase order amounts, and sometimes the shipped quantities do not match the invoiced quantities. You can help manage this information in the following ways:

  - Create a vendor invoice based on product receipts. Product receipts are automatically suggested for invoices, and you can select which product receipts to use. You can also select specific product receipt line items from multiple purchase orders, if you have to. For more information, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).

  - View and approve quantity differences between the invoiced quantity on the invoice and the received quantity on the product receipt. If there is a difference, you can save the invoice and later match it to a different product receipt, or change the invoiced quantity to match the received quantity. For more information, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).

  - Enter invoice amounts that were not included on the original purchase order, so that the invoice information matches the invoice that you received from the vendor. You can compare the charges for purchase orders with the charges for invoices. If necessary, you can add charges to invoices and allocate them to invoice lines. For more information, see [Account for vendor invoice variance due to charges](account-for-vendor-invoice-variance-due-to-charges.md).

  - View and approve price match discrepancies between the invoice net unit price and the purchase order net unit price. You can set up price tolerance percentages for legal entities, vendors, and items. If the vendor invoice line price is not in the acceptable price tolerance, you can save the invoice until it is approved for posting, or until you receive a correction from the vendor. For more information, see [Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md) and [Resolve net unit price invoice matching discrepancies](resolve-net-unit-price-invoice-matching-discrepancies.md).

## See also

[Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md)

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

[Invoice matching details (form)](https://technet.microsoft.com/library/hh209713\(v=ax.60\))

[Invoice totals matching details (form)](https://technet.microsoft.com/library/hh209476\(v=ax.60\))

[Charges totals details/Compare charges values (form)](https://technet.microsoft.com/library/hh242731\(v=ax.60\))

  


