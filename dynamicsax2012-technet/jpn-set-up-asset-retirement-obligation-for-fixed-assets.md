---
title: (JPN) Set up asset retirement obligation for fixed assets
TOCTitle: (JPN) Set up asset retirement obligation for fixed assets
ms:assetid: 78081364-da7c-4af7-9cae-cffec0018bc9
ms:mtpsurl: https://technet.microsoft.com/library/Dn479198(v=AX.60)
ms:contentKeyID: 59633804
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Japan
- ARO
- Forms.AssetDiscountRateSchedule_JP
- Forms.AssetRetirementObligation_JP
- Asset retirement obligation
- ARO document
- Forms.AssetRetirementObligationExplorer_JP
- Forms.AssetRetirementObligationDocument_JP
- retirement obligation
- MsDynAx060.Forms.AssetRetirementObligation_JP
- MsDynAx060.Forms.AssetDiscountRateSchedule_JP
- MsDynAx060.Forms.AssetRetirementObligationDocument_JP
- MsDynAx060.Forms.AssetRetirementObligationExplorer_JP
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up asset retirement obligation for fixed assets 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Asset retirement obligation (ARO) is used to estimate the costs that are related to the future disposal of an asset. ARO is initially recognized as a liability when you acquire or construct a fixed asset. This liability is equal to the present value of the estimated retirement cost for the asset at the beginning of its service life. The estimated retirement cost can change over the course of the asset’s service life based on market discount rates. To accommodate these changes in the liability, you can post retirement costs for the asset as installments at regular intervals of its service life instead of posting the initially recognized liability when you retire the asset.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



You can perform the following tasks to use ARO:

  - Set up a discount rate schedule that uses current market discount rates to calculate ARO amounts.

  - Specify the ARO type to use for an asset, and the frequency at which the changes to the ARO amounts are posted.

  - Set up an estimated retirement cost plan for the ARO and simulate ARO amounts for each fiscal period of the asset’s service life.

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
<li><p>Ensure that you have set up basic fixed asset parameters, such as a default value model, reason codes, and number sequences in the <strong>Fixed assets parameters</strong> form. For more information, see <a href="set-up-fixed-assets-parameters.md">Set up Fixed assets parameters</a>.</p></li>
<li><p>Define a fixed asset group in the <strong>Fixed asset groups</strong> form. For more information, see <a href="https://technet.microsoft.com/library/aa573347(v=ax.60)">Fixed asset groups (form)</a>.</p></li>
<li><p>Set up a fiscal calendar for depreciation. For more information, see <a href="key-tasks-fiscal-calendars-fiscal-years-and-periods.md">Key tasks: Fiscal calendars, fiscal years, and periods</a>.</p></li>
<li><p>Ensure that you have created a fixed asset record. For more information, see <a href="create-a-fixed-asset.md">Create a fixed asset</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a discount rate schedule for ARO

Use the **Discount rates for fixed assets** form to set up a discount rate schedule for the fixed asset that the ARO is applied to. This discount rate schedule is used to maintain the discount rates for the fiscal periods of the fixed asset’s service life.

To set up a discount rate schedule, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Discount rates**.

2.  In the **Start date** field, enter the date from which the discount rate schedule is effective.

3.  In the **Market discount rate percentage** field, enter the current market discount rate percentage for the fixed asset.

You must specify a separate discount rate percentage for each fiscal period of the asset’s service life. To do this, click **New**, and then enter the starting date of the fiscal period in the **Start date** field.

## 2\. Set up an ARO document

Use the **Asset retirement obligation documents** form to set up an ARO document that is attached to the fixed asset. This document contains information about the purpose of the ARO and the posting frequency of the ARO amounts.

To set up an ARO document, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Asset retirement obligation** \> **Asset retirement obligation documents**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Document ID** field, enter a name for the ARO document.

4.  In the **Document date** field, enter the date from which the ARO document is effective.

5.  In the **Posting frequency** field, select the frequency with which the changes that are made to the ARO amounts are posted.

## 3\. Set up ARO for a fixed asset

Use the **Asset retirement obligation** form to set up ARO for a fixed asset. You can also set up an estimated retirement cost plan for the ARO. You can then view the details about the planned amounts and the posted amounts for the retirement cost plan in the **Asset retirement obligation details** form.

To set up ARO for a fixed asset, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select a fixed asset to set up ARO for, and then on the **Action Pane**, click **Asset retirement obligation**.

3.  In the **Asset retirement obligation** form, click **New**.

4.  In the **Value model** field, select the value model of the fixed asset.

5.  In the **Document ID** field, select the name of the asset retirement document to attach to the fixed asset.

6.  On the **Estimated retirement cost plan** FastTab, click **Create**.

7.  In the **Transaction date** field, enter the effective transaction date for the retirement cost plan.

8.  In the **Estimated retirement cost adjustment** field, enter the estimated retirement cost adjustment amount that is required for the ARO.

9.  Click **OK** to create the estimated retirement cost plan.

10. Click **Explore** to open the **Asset retirement obligation details** form, where you can view the planned amounts and the posted amounts for the retirement cost plan.

## Next step

You have finished setting up ARO for the fixed asset. You can now depreciate and amortize the fixed asset and settle the ARO. For more information, see [(JPN) Depreciate and retire a fixed asset with asset retirement obligation](jpn-depreciate-and-retire-a-fixed-asset-with-asset-retirement-obligation.md).

## Related tasks

[Set up number sequences for Fixed assets](set-up-number-sequences-for-fixed-assets.md)

[Set up depreciation profiles](set-up-depreciation-profiles.md)

[Set up value models](set-up-value-models.md)

[Set up fixed asset groups](set-up-fixed-asset-groups.md)

[Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md)

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
<td><p>To perform this task, you must be a member of the <strong>-SYSADMIN-</strong> security role.</p></td>
</tr>
</tbody>
</table>

  


