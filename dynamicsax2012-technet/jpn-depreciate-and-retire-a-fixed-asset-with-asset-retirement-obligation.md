---
title: (JPN) Depreciate and retire a fixed asset with asset retirement obligation
TOCTitle: (JPN) Depreciate and retire a fixed asset with asset retirement obligation
ms:assetid: 0b24253e-e4d6-4563-931e-8d5fb76da572
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn479197(v=AX.60)
ms:contentKeyID: 59633803
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation
- Forms.AssetBookTable
- Forms.AssetProfile
- Forms.AssetBook
- Forms.LedgerJournalTable
- Forms.AssetTable
- Forms.LedgerJournalTransAsset
- Japan
- ARO
- asset retirement obligation
- amortize
- Depreciate
- retire
- MsDynAx060.Forms.AssetBookTable
- MsDynAx060.Forms.LedgerJournalTransAsset
---

# (JPN) Depreciate and retire a fixed asset with asset retirement obligation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you set up an asset retirement obligation (ARO) document and attach it to a fixed asset, you can acquire a fixed asset and generate an ARO transaction during the acquisition. You can adjust ARO amounts up or down to calculate interest expenses in case there are changes in the estimated retirement cost for the fixed asset. You can depreciate the fixed asset over the course of its useful life, and then retire the asset.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



When you acquire a fixed asset, you can generate an ARO transaction to post the ARO amounts to the ledger during the acquisition. To do this, when you create an acquisition journal for the fixed asset, click **Functions** \> **Generate asset retirement obligation transactions** on the **Journal voucher** form. The ARO transactions are created in the **Journal voucher** form based on the ARO document that you attached to the fixed asset. You can then post the ARO transactions by clicking **Post**. For more information, see [Journal voucher - Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620564\(v=ax.60\)).

Follow the steps in this topic to generate an ARO proposal for an interest expense, retire a fixed asset, and view ARO settlement amounts.

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
<td><p>Ensure that you have set up basic fixed asset parameters, such as a default value model, reason codes, and number sequences, in the <strong>Fixed assets parameters</strong> form. For more information, see <a href="set-up-fixed-assets-parameters.md">Set up Fixed assets parameters</a>.</p>
<p>Define a fixed asset group in the <strong>Fixed asset groups</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa573347(v=ax.60)">Fixed asset groups (form)</a>.</p>
<p>Set up a fiscal calendar for depreciation. For more information, see <a href="key-tasks-fiscal-calendars-fiscal-years-and-periods.md">Key tasks: Fiscal calendars, fiscal years, and periods</a>.</p>
<p>Ensure that you have created a fixed asset record. For more information, see <a href="create-a-fixed-asset.md">Create a fixed asset</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Depreciation setup tasks</strong></p></td>
<td><p>Set up depreciation rules for fixed assets. For more information, see <a href="jpn-set-up-depreciation-and-depreciation-methods.md">(JPN) Set up depreciation and depreciation methods</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>ARO-related setup task</strong></p></td>
<td><p>Set up a discount rate schedule and an ARO document, and attach the ARO document to a fixed asset. For more information, see <a href="jpn-set-up-asset-retirement-obligation-for-fixed-assets.md">(JPN) Set up asset retirement obligation for fixed assets</a>.</p></td>
</tr>
</tbody>
</table>


## Generate an ARO proposal for an interest expense

Use the **Journal voucher** form to generate an ARO proposal for an interest expense, and then post the interest expense. You can generate this proposal at the end of each quarter or fiscal year of the asset’s useful life.

To generate the ARO proposal for an interest expense, follow these steps:

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Select the fixed asset to generate the proposal for, and then click **Lines**.

3.  In the **Journal voucher** form, select the acquisition journal that is used to acquire the fixed asset, and then click, **Proposals** \> **Asset retirement obligation - accretion expense**.
    

    > [!NOTE]
    > <P>You must use this option only when the acquisition date and the date when ARO is recognized for the asset are on the same day. If ARO is recognized after the acquisition date, you must click <STRONG>Proposals</STRONG> &gt; <STRONG>Capitalized asset retirement obligation</STRONG>.</P>



4.  In the **To date** field, select the ending date of the period to generate the proposal for.

5.  Click **Select** to specify a query to filter the assets that are included in the proposal, and then click **OK**.

6.  In the **Asset retirement obligation - accretion expense** form, click **OK** to generate the interest expense proposal.

7.  In the **Journal voucher** form, click **Post** to post the journal.

You can use the **Asset retirement obligation details** form to view the posted ARO amounts for the fixed asset. For more information, see [(JPN) Set up asset retirement obligation for fixed assets](jpn-set-up-asset-retirement-obligation-for-fixed-assets.md).

## Retire a fixed asset and view ARO settlement amounts

After you depreciate the asset and post subsequent ARO amounts over the course of the asset’s useful life, you can use the **Fixed asset posting profiles** form to retire the asset. For more information, see [About fixed asset disposal](about-fixed-asset-disposal.md).

After you retire the asset, you can use the **Value models** form to view the ARO settlement amounts.

To view ARO settlement amounts, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the fixed asset that you retired, and then click **Value models**.

3.  In the **Value models** form, click **Inquiry** \> **Profile**.

4.  In the **Profile** form, in the **Amortization of asset retirement obligation** field, you can view the ARO settlement amounts for each month of the fixed asset’s useful life.

## Related tasks

[Dispose of or retire assets overview](dispose-of-or-retire-assets-overview.md)

[Revalue assets overview](revalue-assets-overview.md)

[Split assets overview](split-assets-overview.md)

[Transfer or lend assets overview](transfer-or-lend-assets-overview.md)

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
<td><p>Ensure that the <strong>Asset</strong> configuration key is available under the <strong>Data Dictionary</strong> &gt; <strong>Configuration Keys</strong> node in the Application Object Tree.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following duties.</p>
<ul>
<li><p><strong>Inquire into fixed assets</strong> (AssetFixedAssetsInquire)</p></li>
<li><p><strong>Maintain fixed assets</strong> (AssetFixedAssetsMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p><strong>View asset retirement obligation transactions</strong> (AssetRetirementObligationView_JP)</p></li>
<li><p><strong>Maintain asset retirement obligation transactions</strong> (AssetRetirementObligationMaintain_JP)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

