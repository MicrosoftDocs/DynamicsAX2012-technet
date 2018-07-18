---
title: "What's new: Fixed assets features"
TOCTitle: Fixed assets features
ms:assetid: 74ee3d99-ba02-4483-b50f-fe5c109e0f69
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527135(v=AX.60)
ms:contentKeyID: 59623264
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Fixed assets features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Fixed assets](fixed-assets.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

## What’s new in AX 2012

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
<td><p>Transfer fixed assets between locations, funds, programs, and departments.</p></td>
<td><p>You can transfer fixed assets between financial dimensions, such as locations, funds, programs, and departments. For each transfer, a historical record is created that includes the transaction date (transfer date) and the amount at the time of the transfer. You can view the historical information in the <strong>Fixed assets</strong> form. This form provides the clear record of asset transfers that is required for high-value assets. Alternatively, you can use this tracking method in the <strong>Value models</strong> form. In this form, you can also modify the financial dimensions for a fixed asset when you do not have to keep a historical record of the changes because no record of the transfer details is required.</p>
<p>For more information, see <a href="transfer-fixed-assets.md">Transfer fixed assets</a>.</p></td>
</tr>
<tr class="even">
<td><p>Attributes for asset activity codes, property groups, and organization units are available for fixed assets.</p></td>
<td><p>Some organizations must track fixed assets at a very detailed level, either because of specialized business required or to comply with governmental regulations. You can track fixed assets by using three new attributes: the asset activity code, property group, and organization unit. After you create these attributes in their setup forms, you can assign them to fixed assets in the <strong>Fixed assets</strong> form.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="set-up-asset-activity-codes.md">Set up asset activity codes</a></p></li>
<li><p><a href="set-up-property-groups.md">Set up property groups</a></p></li>
<li><p><a href="create-a-fixed-asset.md">Create a fixed asset</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>New Microsoft SQL Server Reporting Services reports for fixed assets</p></td>
<td><p>You can use physical inventory worksheets as checklists to identify and list assets. The <strong>Fixed asset due for replacement</strong> report lists assets that are due to be replaced, based on the asset replacement dates.</p>
<p>For more information, see <a href="fixed-assets-reports.md">Fixed assets reports</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

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
<td><p>Transfer multiple fixed assets.</p></td>
<td><p>You can now transfer more than one fixed asset at the same time. For fewer than 100 assets, you can complete the transfer from the <strong>Fixed assets</strong> list page. For more than 100 assets, use the <strong>Mass transfer</strong> form that is available in the <strong>Periodic</strong> section of the <strong>Fixed assets</strong> area page.</p>
<p>For more information, see <a href="transfer-fixed-assets.md">Transfer fixed assets</a>.</p></td>
</tr>
<tr class="even">
<td><p>The acquisition cost of fixed assets can include a miscellaneous charge amount.</p></td>
<td><p>In earlier releases of Microsoft Dynamics AX, when a fixed asset was acquired, and the acquisition cost included miscellaneous charges, the acquisition amount of the fixed asset was adjusted to exclude the miscellaneous charges. Now, when a fixed asset is acquired through a vendor invoice, any item type miscellaneous charge amounts are included in the acquisition cost of the fixed asset.</p></td>
</tr>
<tr class="odd">
<td><p>The process for acquisition proposals or depreciation proposals for fixed assets can now be run in a batch process.</p></td>
<td><p>In earlier releases of AX 2012, the processes for depreciation and acquisition proposals could be very time-consuming. Now, you can create depreciation or acquisition proposals as a periodic process. After the process is run, journals are created, so that users can review the transactions before they post. For longer running proposals, such as depreciation proposals, you can select to create the proposals using a batch process.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="propose-fixed-asset-acquisitions.md">Propose fixed asset acquisitions</a></p></li>
<li><p><a href="propose-depreciation-for-fixed-assets.md">Propose depreciation for fixed assets</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

  


