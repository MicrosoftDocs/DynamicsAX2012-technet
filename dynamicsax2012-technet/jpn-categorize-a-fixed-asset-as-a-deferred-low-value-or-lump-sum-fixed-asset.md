---
title: (JPN) Categorize a fixed asset as a deferred, low value, or lump sum fixed asset
TOCTitle: (JPN) Categorize a fixed asset as a deferred, low value, or lump sum fixed asset
ms:assetid: 2d7e57e3-9db5-4dbf-bb38-3f5ac6019544
ms:mtpsurl: https://technet.microsoft.com/library/Dn716011(v=AX.60)
ms:contentKeyID: 62200254
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.AssetTableListPage
- fixed asset
- Forms.AssetTable
- lump sum
- categorize a fixed asset
- low value
- deferred
audience: Application User
ms.search.region: Japan
---

# (JPN) Categorize a fixed asset as a deferred, low value, or lump sum fixed asset 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to categorize a fixed asset as a deferred, low value, or lump sum fixed asset. You can then calculate the depreciation amount of the fixed asset, and track and report the fixed asset over one or more fiscal periods. For more information, see [(JPN) Equally divided depreciation method](jpn-equally-divided-depreciation-method.md).

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
<td><p>The primary address for the legal entity must be in the following countries/regions: Japan</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up a fiscal calendar. For more information, see <a href="key-tasks-fiscal-calendars-fiscal-years-and-periods.md">Key tasks: Fiscal calendars, fiscal years, and periods</a>.</p></li>
<li><p>Set up a value model to track the financial value of a fixed asset over a period of time. For more information, see <a href="set-up-value-models.md">Set up value models</a>.</p></li>
<li><p>Set up a fixed asset group to group fixed assets. For more information, see <a href="set-up-fixed-asset-groups.md">Set up fixed asset groups</a>.</p></li>
<li><p>Set up a posting profile to specify the ledger accounts to which fixed asset transactions are posted. For more information, see <a href="set-up-fixed-asset-posting-profiles.md">Set up fixed asset posting profiles</a>.</p></li>
<li><p>Set up a depreciation profile for the equally divided depreciation method. For more information, see <a href="jpn-set-up-depreciation-and-depreciation-methods.md">(JPN) Set up depreciation and depreciation methods</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Categorize a fixed asset as a deferred fixed asset

Use the **Fixed asset** form to categorize a fixed asset as a deferred fixed asset.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select or create a fixed asset, and then click **Edit**. For more information, see [Create a fixed asset](create-a-fixed-asset.md).

3.  In the **Type** field, select **Deferred** to categorize the fixed asset as a deferred fixed asset.

4.  In the **Deferred type** field, select one of the following options to indicate the depreciation technique to apply to the deferred fixed asset:
    
      - **Equally divided** – The depreciation amount is equally divided among all of the fiscal periods within the useful life of the fixed asset.
    
      - **One time** – The depreciation amount is manually applied for each fiscal period within the useful life of the fixed asset.


> [!NOTE]
> <P>The <STRONG>Deferred type</STRONG> field is available only if you select <STRONG>Deferred</STRONG> in the <STRONG>Type</STRONG> field.</P>



## Categorize a fixed asset as a low value or a lump sum fixed asset

Use the **Fixed asset** form to categorize a fixed asset as a low value or a lump sum fixed asset.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select or create a fixed asset, and then click **Edit**. For more information, see [Create a fixed asset](create-a-fixed-asset.md).

3.  In the **Type** field, select **Tangible**, **Intangible**, **Financial**, **Land and buildings**, **Goodwill**, or **Other** as the fixed asset type.

4.  In the **Asset classification** field, select one of the following options to classify the fixed asset depending on the acquisition value of the fixed asset:
    
      - **Low value** – Categorize the fixed asset as a low value fixed asset.
    
      - **Lump sum** – Categorize the fixed asset as a lump sum fixed asset.
    

    > [!NOTE]
    > <P>The <STRONG>Asset classification</STRONG> field is available only if you select <STRONG>Tangible</STRONG>, <STRONG>Intangible</STRONG>, <STRONG>Financial</STRONG>, <STRONG>Land and buildings</STRONG>, <STRONG>Goodwill</STRONG>, or <STRONG>Other</STRONG> as the fixed asset type in the <STRONG>Type</STRONG> field.</P>



## Related tasks

[(JPN) Set up depreciation and depreciation methods](jpn-set-up-depreciation-and-depreciation-methods.md)

[(JPN) Configure and calculate fixed asset depreciation](jpn-configure-and-calculate-fixed-asset-depreciation.md)

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
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To create a deferred, low value, or lump sum fixed asset, you must be a member of a security role that includes the following duties:</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Inquire into fixed assets</strong></p></td>
<td><p>AssetFixedAssetsInquire</p></td>
<td><p>Create a fixed asset</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain fixed assets</strong></p></td>
<td><p>AssetFixedAssetsMaintain</p></td>
<td><p>Maintain fixed assets</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create a deferred, low value, or lump sum fixed asset, you must be a member of a security role that includes the following privileges:</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>View fixed asset records</strong></p></td>
<td><p>AssetTableView</p></td>
<td><p>View the fixed asset records</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain fixed asset records</strong></p></td>
<td><p>AssetTableMaintain</p></td>
<td><p>Maintain fixed asset records</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


