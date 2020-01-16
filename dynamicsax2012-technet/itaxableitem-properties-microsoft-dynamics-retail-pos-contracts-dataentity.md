---
title: ITaxableItem Properties (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ITaxableItem Properties
ms:assetid: Properties.T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem_properties(v=AX.60)
ms:contentKeyID: 47128216
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ITaxableItem Properties

The [ITaxableItem](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) type exposes the following members.

## Properties

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-begindatetime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BeginDateTime</a></td>
<td>The start date and time of the transaction.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-enddatetime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">EndDateTime</a></td>
<td>The end date and time of the transaction.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-grossamount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">GrossAmount</a></td>
<td>Gets or sets the gross amount.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-itemgroupid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ItemGroupId</a></td>
<td><strong>Obsolete.</strong> The retail group of the item.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-itemid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ItemId</a></td>
<td>The item ID stored in the ERP system.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-netamountperunit-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NetAmountPerUnit</a></td>
<td>Gets the net amount per unit.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-netamountwithallinclusivetaxperunit-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NetAmountWithAllInclusiveTaxPerUnit</a></td>
<td>Gets the net amount per unit with all inclusive taxes (even non-exempt).</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-price-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Price</a></td>
<td>Gets or sets the price.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-quantity-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Quantity</a></td>
<td>Gets or sets the quantity.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-retailtransaction-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">RetailTransaction</a></td>
<td>Gets or sets the transaction.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-salesorderunitofmeasure-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SalesOrderUnitOfMeasure</a></td>
<td>The active item sale unit of measurement (based upon UOM set for the item by the user).</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-salestaxgroupid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SalesTaxGroupId</a></td>
<td>Gets or sets the sales tax group ID.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-salestaxgroupidoriginal-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SalesTaxGroupIdOriginal</a></td>
<td>Gets or sets the original sales tax group ID.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-taxamount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxAmount</a></td>
<td>Gets the total tax amount, which is the accumulation of TaxAmountInclusive + TaxAmountExclusive.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-taxamountexclusive-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxAmountExclusive</a></td>
<td>The tax amount that comes from an exclusive tax code, which indicates that an item price does not include tax. For example, for an item that is priced at $11.00, a tax exclusive rate equaling 10% would result in a tax of $1.10 (.10*11.00).</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-taxamountexemptinclusive-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxAmountExemptInclusive</a></td>
<td>The tax amount coming from inclusive tax codes that is exempt for a particular transaction. This can occur if the customer is a non-taxed organization.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-taxamountinclusive-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxAmountInclusive</a></td>
<td>The tax amount coming from inclusive tax codes, which indicates that an item price includes sales tax. For example, for an item that is priced at $11.00, a tax inclusive rate equaling 10% would indicate a tax of 1.00 added to a base price of 10.00.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-taxgroupid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxGroupId</a></td>
<td>Gets or sets the tax group ID.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-taxgroupidoriginal-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxGroupIdOriginal</a></td>
<td>Gets or sets the original tax group ID.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-taxlines-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxLines</a></td>
<td>Gets the tax lines.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="itaxableitem-taxratepct-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxRatePct</a></td>
<td>Gets or sets the tax rate percentage.</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

