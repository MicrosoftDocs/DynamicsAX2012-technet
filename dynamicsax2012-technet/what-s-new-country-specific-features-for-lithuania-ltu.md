---
title: "What's new: Country-specific features for Lithuania (LTU)"
TOCTitle: Country-specific features for Lithuania
ms:assetid: 717321bd-40f5-4702-b99c-4ebb516f1154
ms:mtpsurl: https://technet.microsoft.com/library/Dn527134(v=AX.60)
ms:contentKeyID: 59623263
author: Khairunj
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for Lithuania (LTU) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we changed and added country-specific functionality for Lithuania. For more information, see the tables that apply to your version of the product.

For more information about specific features for Lithuania, see [TechNet Library for Application Users - Lithuania](https://go.microsoft.com/fwlink/?linkid=299916).

## What’s new in AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use the <strong>Repair</strong> form under <strong>Fixed assets</strong> &gt; <strong>Value models</strong> form to record repairs that are made to fixed assets.</p></td>
<td><p>In AX 2012 R2, repair expenses can be tracked, viewed, and reported. This feature lets users make adjustments to an asset's net book value if the amount for the repair reaches a threshold that is specified by the authorities.</p>
<p>For more information, see <a href="ltu-enter-details-for-a-fixed-asset-repair-statement.md">(LTU) Enter details for a fixed asset repair statement</a> and <a href="ltu-generate-the-fixed-asset-repair-report.md">(LTU) Generate the fixed asset repair report</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enter packing slip details for the transfer of fixed assets to a different location.</p></td>
<td><p>If a company moves a fixed asset from one department to another department, and those departments are not in the same location, a packing slip must be printed that contains specific information.</p>
<p>In addition, the packing slip for the transportation of fixed assets must be numbered. You can select whether to use an automatic numbering sequence or assign packing slip numbers manually.</p>
<p>You can use the <strong>Change fixed asset group</strong> form to add a new asset to an asset group, You can also use this form to transfer an existing asset to a different group and, optionally, assign a new fixed asset number.</p>
<p>You can use the <strong>Warehouse transfer</strong> form to transfer multiple assets by fixed asset group.</p>
<p>You can use the <strong>Fixed asset transfer</strong> form to record the transfer information. To enter the required information for the packing slip, on the <strong>Packing slip details</strong> tab, select the <strong>Packing slip</strong> check box to make the fields in the <strong>Replace with</strong> group available.</p>
<p>You can use the <strong>Packing slip details</strong> form to enter transportation details and print the packing slip.</p>
<p>For more information, see <a href="ltu-change-the-fixed-asset-group-for-a-fixed-asset.md">(LTU) Change the fixed asset group for a fixed asset</a>, <a href="ltu-create-a-transfer-packing-slip-for-a-fixed-asset.md">(LTU) Create a transfer packing slip for a fixed asset</a>, and <a href="ltu-review-the-asset-packing-slip-details-and-print-the-packing-slip.md">(LTU) Review the asset packing slip details and print the packing slip</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to invoice numbering and packing slip registration.</p></td>
<td><p>You can define number sequences for sales and purchase invoices. You can also define numbering for users and user groups, and for specific customer and vendor groups. The numbers are printed on invoice layouts, invoice registers, and packing slip registration journal reports.</p>
<p>You can also enter invoice and packing slip numbers manually. If you enter the numbers manually, you can verify the numbers for invoices and packing slips to make sure that the numbers are unique.</p>
<p>For more information, see <a href="ltu-setting-up-number-sequences.md">(LTU) Setting up number sequences</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 9

The procedure for submitting Intrastat returns in Lithuania has changed due to adoption of euro currency. The invoice value and statistical value in the Intrastat declarations and modified declarations, submitted by VAT payers for the reference period since the adoption of euros (January 1, 2015) in the Republic of Lithuania must be selected in the Intrastat declarations in euro. The IDAIS system was updated so that euros are accepted on the Intrastat declarations and submitted by VAT payers in the XML files for the format which corresponds to the new instat.xml data structure. The update provides the ability to create Intrastat declarations in new the XML format.

  


