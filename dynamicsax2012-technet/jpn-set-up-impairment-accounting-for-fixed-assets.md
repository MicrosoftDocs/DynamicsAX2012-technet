---
title: (JPN) Set up impairment accounting for fixed assets
TOCTitle: (JPN) Set up impairment accounting for fixed assets
ms:assetid: c88ab5ee-6e1e-4813-95d8-812fcc4d444b
ms:mtpsurl: https://technet.microsoft.com/library/Dn532268(v=AX.60)
ms:contentKeyID: 59930767
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Fixed asset
- Forms.AssetPosting
- fixed assets
- Forms.AssetTableListPage
- Forms.AssetBook
- Forms.AssetTable
- Japan
- impaired asset
- impaired assets
- Impairment
- impairment accounting
- impairments
- JP - 00014
- Forms.AssetImpairmentIndicator_JP
- impairment indicator
- impairment indicators
- indicator
- indicators
- MsDynAx060.Forms.AssetPosting
- MsDynAx060.Forms.AssetBook
- MsDynAx060.Forms.AssetTable
- MsDynAx060.Forms.AssetImpairmentIndicator_JP
- MsDynAx060.Forms.AssetTableListPage
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up impairment accounting for fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to set up a posting profile for impairment accounting and update impairment indicators to calculate fixed asset impairments. For more information about impairment accounting, see [(JPN) Impairment accounting for fixed assets](jpn-impairment-accounting-for-fixed-assets.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



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
<td><p>The primary address for the legal entity must be in the following countries/regions: Japan</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up fixed asset groups. For more information, see <a href="set-up-fixed-asset-groups.md">Set up fixed asset groups</a>.</p></li>
<li><p>Set up a fiscal calendar and assign the calendar to a ledger. For more information, see <a href="about-fiscal-calendars-fiscal-years-and-periods.md">About fiscal calendars, fiscal years, and periods</a> and <a href="select-a-fiscal-calendar-for-a-ledger.md">Select a fiscal calendar for a ledger</a>.</p></li>
<li><p>Create a fixed asset in the <strong>Fixed assets</strong> form. For more information, see <a href="create-a-fixed-asset.md">Create a fixed asset</a>.</p></li>
<li><p>Set up value models in the <strong>Value models</strong> form. For more information, see <a href="set-up-value-models.md">Set up value models</a>.</p></li>
<li><p>Set up depreciation books in the <strong>Depreciation books</strong> form. For more information, see <a href="set-up-asset-depreciation-books.md">Set up asset depreciation books</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a posting profile for impairment accounting

Use the **Fixed asset posting profiles** form to set up a posting profile for impairment accounting.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**.

2.  Click **New** or press CTRL+N to create a posting profile for impairment accounting. Alternatively, you can select an existing posting profile.

3.  In the **Posting profile** and **Description** fields, enter an identification code and a description of the posting profile.

4.  In the **Value model** field, select a value model to apply to impairment transactions.

5.  In the **Groupings** field, select the grouping level to set up a main account to post impairment transactions to.
    
    Select from the following options:
    
      - **Table** – Select a main account for each fixed asset.
    
      - **Group** – Select a main account for each fixed asset group.
    
      - **All** – Select a main account for all of the fixed assets.

6.  In the **Fixed asset number** field, select a fixed asset or a fixed asset group for the impairment transactions. The values in this field are determined by the selection in the **Groupings** field.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Groupings</STRONG> field.</P>



7.  In the **Main account** and **Offset account** fields, select the default main account and the default offset account that are used to post the impairment transactions.

## 2\. Update impairment indicators for a fixed asset

Use the **Update impairment indicators** form to update the impairment indicators, such as undiscounted cash flow for a fixed asset.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**. Select or create a fixed asset, and then click **Value models**. In the **Value models** form, select or create a value model record, and then click **Functions** \> **Update impairment indicators**.

2.  Click **New** or press CTRL+N to create an impairment indicator record. The **Fixed asset number**, **Book**, and **Book type** fields are updated automatically.

3.  In the **Modify date** field, select the date from which to apply the impairment indicator to the fixed asset.

4.  In the **Undiscounted cash flow** field, enter the undiscounted cash flow, or in the **Recoverable amount** field, enter the recoverable amount. The **Line number** field is automatically updated with the next line number in the sequence. You can only modify or delete the line that has the highest line number.

You can click **Attachments** in the **Update impairment indicators** form to open the **Fixed asset number** form, where you can attach a document to the impairment indicator. For more information, see [Document handling (form)](https://technet.microsoft.com/library/aa616432\(v=ax.60\)).

## 3\. Update impairment indicators for multiple fixed assets

Use the **Update impairment indicators** form to update the impairment indicators, such as undiscounted cash flow for multiple fixed assets.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Periodic** \> **Impairment** \> **Review impairment indicators**.

2.  Click **New** or press CTRL+N to create an impairment indicator record.

3.  In the **Modify date** field, select the date from which to apply the impairment indicator to the fixed asset.

4.  In the **Fixed asset number** field, select the identification code of the fixed asset number.

5.  In the **Book** field, select the identification code of a value model or a depreciation book. The **Book type** field is updated depending on your selection in the **Book** field.

6.  In the **Undiscounted cash flow** field, enter the undiscounted cash flow, or in the **Recoverable amount** fields, enter the recoverable amount. The **Line number** field is automatically updated with the next line number in the sequence. You can only modify or delete the line that has the highest line number.

7.  Repeat steps 2 through 6 to update additional impairment indicators for fixed assets.

8.  Click **Function** \> **Update indicator** to update the impairment indicators for the fixed assets.

## Next step

You have finished setting up impairment accounting for fixed assets. You can identify impaired fixed assets, and then post journals for impaired fixed assets. For more information, see [(JPN) Identify impaired assets and post journals for impairment](jpn-identify-impaired-assets-and-post-journals-for-impairment.md).

## Related tasks

[(JPN) Set up depreciation and depreciation methods](jpn-set-up-depreciation-and-depreciation-methods.md)

[(JPN) Fixed asset depreciation](jpn-fixed-asset-depreciation.md)

[(JPN) Asset retirement obligation for fixed assets](jpn-asset-retirement-obligation-for-fixed-assets.md)

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
<td><p>Ensure that the <strong>Asset</strong> configuration key is available under the <strong>Data Dictionary</strong> &gt; <strong>Configuration Keys</strong> node in the Application Object Tree (AOT).</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the <strong>Manage fixed asset impairment</strong> (AssetFixedAssetImpairmentManage_JP) duty.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>Maintain the indicators for doing impairment review and test</strong> (AssetImpairmentIndicatorMaintain_JP)</p></li>
<li><p><strong>View the indicators for doing impairment review and test</strong> (AssetImpairmentIndicatorView_JP)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


