---
title: (IND) About recalculation of indirect taxes
TOCTitle: (IND) About recalculation of indirect taxes
ms:assetid: c3d8058e-a09f-4d9a-b20b-df4b2abf3e95
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ730998(v=AX.60)
ms:contentKeyID: 49675240
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) About recalculation of indirect taxes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Sometimes, when a transaction is posted, the taxes that are included in the transaction must be recalculated. Indirect taxes, such as excise tax, service tax, and value-added tax (VAT), and the information that is entered in specific fields will cause taxes to be recalculated when a an invoice is generated for the transaction. The information is then updated in the **Temporary sales tax transactions** form. When the transaction invoice is posted, the information in the **Temporary sales tax transactions** form will be included in when the invoice is posted.

To enable the calculation or recalculation of taxes with regard to indirect taxes, you must enable each tax type to include in the recalculation. You can enable these indirect taxes in the **Sales tax** area of the **General ledger parameters** form under the **Apply India taxes** field group.

The sections in this topic list the forms and fields that will cause the indirect taxes to be recalculated.

## Purchase order form

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Header view fields</p></th>
<th><p>Line view fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Vendor account</strong></p></td>
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Price group</strong></p></td>
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Line discount group</strong></p></td>
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Multiline disc. group</strong></p></td>
<td><p><strong>Discount</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Total discount group</strong></p></td>
<td><p><strong>Discount percentage</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Total discount %</strong></p></td>
<td><p><strong>Multiline discount</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Multiline discount percentage</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Max. retail price in customs currency</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Form type</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Excise record type</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Direct settlement</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>CENVAT credit availed</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
</tbody>
</table>


## Vendor invoice form

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Header view fields</p></th>
<th><p>Line view fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Invoice account</strong></p></td>
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Discount</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Discount percentage</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Multiline discount</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Multiline discount percentage</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Form type</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Excise record type</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><strong>Direct settlement</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>CENVAT credit availed</strong></p></td>
</tr>
</tbody>
</table>


## Purchase requisition form

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Form type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise record type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
</tbody>
</table>


## Journal voucher - Invoice journal form

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Customs tariff direction</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>India sales tax form type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise record type</strong></p></td>
</tr>
</tbody>
</table>


## Journal voucher - Invoice register form

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Customs tariff direction</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>India sales tax form type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise record type</strong></p></td>
</tr>
</tbody>
</table>


## Journal voucher - Invoice approval journal form

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash discount</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Customs tariff direction</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>India sales tax form type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise record type</strong></p></td>
</tr>
</tbody>
</table>


## General journal form

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Customs tariff direction</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>India sales tax form type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise record type</strong></p></td>
</tr>
</tbody>
</table>


## Vendor payment journal form

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Form type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise record type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Customs tariff direction</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
</tbody>
</table>


## Customer payment journal form

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>VAT items type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Non recoverable pct.</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Form type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise record type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Customs tariff direction</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
</tbody>
</table>


## Free text invoice form

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Fields</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Sales tax group</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Item sales tax group</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise tariff code</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Customs tariff code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>India sales tax form type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Assessable value</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Max. retail price per unit</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Max. retail price</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Location</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Tax information</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Excise type</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Excise record type</strong></p></td>
</tr>
</tbody>
</table>

  


