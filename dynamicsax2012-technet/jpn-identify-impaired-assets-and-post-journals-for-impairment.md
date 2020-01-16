---
title: (JPN) Identify impaired assets and post journals for impairment
TOCTitle: (JPN) Identify impaired assets and post journals for impairment
ms:assetid: 836d62b1-bc88-470a-b56a-70261da6626d
ms:mtpsurl: https://technet.microsoft.com/library/Dn530767(v=AX.60)
ms:contentKeyID: 59683045
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- fixed assets
- fixed asset
- Forms.LedgerJournalTable
- Forms.AssetDepBookJournalTrans
- Forms.LedgerJournalTransAsset
- Forms.AssetDepBookJournalTable
- Japan
- asset impairment
- impaired asset
- Impairment
- Impaired assets
- Forms.AssetImpairmentRecognitionTest_JP
- Impairments
- Impairment accounting
- JP - 00014
- Forms.AssetImpairmentReview_JP
audience: Application User
ms.search.region: Japan
---

# (JPN) Identify impaired assets and post journals for impairment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to generate a list of fixed assets that are possibly impaired, run the impairment recognition test to generate a list of impaired fixed assets, and then create and post journals for fixed asset impairments.


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
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up impairment accounting for fixed assets. For more information, see <a href="jpn-set-up-impairment-accounting-for-fixed-assets.md">(JPN) Set up impairment accounting for fixed assets</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Generate a list of fixed assets that are possibly impaired

Use the **Impairment review** form to generate a list of fixed assets that are possibly impaired and a list of transactions for review purposes. You can review the fixed assets and transactions, and then generate a report for distribution, receiving, or other purposes, if required.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Periodic** \> **Impairment** \> **Impairment management**.

2.  In the **Book type** field, select **Value model** or **Depreciation book** as the book type to review impairments for.

3.  On the **Carrying amount overview** FastTab, click **Query**, and then specify the criteria, such as fixed asset numbers, fixed asset groups, or value models to generate the list of fixed assets. Click **OK**. The list of fixed assets that are to be reviewed is updated on the **Carrying amount overview** FastTab in the **Impairment review** form.

4.  Click **Specify percentage**, and then in the **Percentage** field, enter the percentage of fixed assets from the list of fixed assets to review impairments for.

5.  On the **Transaction analysis overview** FastTab, click **Query**, and then specify the criteria, such as fixed asset numbers, fixed asset groups, or value models to generate the list of fixed asset transactions. Click **OK**. The list of fixed asset transactions that are to be reviewed is updated on the **Transaction analysis overview** FastTab in the **Impairment review** form. It is not mandatory to generate a list of transactions. However, you can use the transactions to review the fixed assets.

6.  Select a fixed asset on the **Carrying amount overview** FastTab or select a transaction on the **Transaction analysis overview** FastTab, and then click **Generate report** to generate a report, if required.

You can select fixed assets in the **Impairment review** form, and then click **Update impairment indicators** to open the **Update impairment indicators** form, where you can update the impairment indicators for the fixed assets.

## 2\. Run a recognition test to identify assets for impairment accounting

Use the **Impairment recognition test** form to run the impairment recognition test using the impairment indicators to generate a list of impaired fixed assets.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Periodic** \> **Impairment** \> **Run recognition test**.

2.  In the **Book type** field, select **Value model** or **Depreciation book** as the book type to run the impairment recognition test for.

3.  In the **From date** and **To date** fields, specify the starting date and ending date of the period for the impairment recognition test.

4.  Click **Query** to open the **Inquiry** form, where you can specify the criteria, such as fixed asset numbers, fixed asset groups, and posting layers to run the recognition test for.

5.  Click **OK**.

6.  In the **Impairment recognition test** form, you can verify the list of impaired fixed assets that is updated.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Fixed asset group</strong></p></td>
    <td><p>The group that the fixed asset belongs to.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Fixed asset number</strong></p></td>
    <td><p>The identification number of the fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Book</strong></p></td>
    <td><p>The identification code of the value model or depreciation book.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Book type</strong></p></td>
    <td><p>The book type for the fixed asset. The options are <strong>Value model</strong> and <strong>Depreciation book</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Status</strong></p></td>
    <td><p>The status of the fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Acquisition price</strong></p></td>
    <td><p>The amount that is paid to acquire the fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Net book value</strong></p></td>
    <td><p>The net book value of the fixed asset. This is the outstanding value of the fixed asset, including the scrap value.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Expected scrap value</strong></p></td>
    <td><p>The expected scrap value of the fixed asset. This is part of the acquisition price, which is the value of the fixed asset at the end of its service life.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Impairment</strong></p></td>
    <td><p>The impairment write-down amount for the fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Undiscounted cash flow</strong></p></td>
    <td><p>The undiscounted cash flow amount for the fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Recoverable amount</strong></p></td>
    <td><p>The recoverable amount for the fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Impairment adjustment amount</strong></p></td>
    <td><p>The calculated impairment adjustment amount for the fixed asset.</p></td>
    </tr>
    </tbody>
    </table>


7.  To save the test results for later use, perform these steps:
    
    1.  Click **Save impairment**, and then in the **Impairment test ID** field, enter an identification code for the test result record.
    
    2.  In the **Description** field, enter a description of the test result record.
    
    3.  In the **Date** field, enter the date to save the test result record.

## 3\. Create and post a journal for fixed asset impairments

Use the **Depreciation book journal** or **Fixed assets** form to create and post journal transactions for impaired fixed assets. You can specify details about the impairment before you post the journal.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Journals** \> **Depreciation book journal**.
    
    –or–
    
    Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Create a journal. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).

3.  Click **Lines** to open the **Journal line** form or the **Journal voucher** form, and then click **Proposals** \> **Impairment proposal**.

4.  In the **Select from the saved impairment test results** dialog box, in the **Impairment test ID** field, select the identification code of the impairment test to create the journal for.

5.  Click **OK** to create journal lines in the **Journal line** form, depending on the information that is available in the impairment test record that you select. You can modify the details about the impairment before you post the journal, if required.

6.  Click **Validate** to validate the depreciation book journal lines or fixed asset journal lines.

7.  Click **Post** \> **Post** to post the journal.

You can view the amount for the impairment transactions for a fixed asset in the **Write down adjustment** field in the **Fixed asset balances** form.

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
<li><p><strong>Generate asset impairment recognition test result</strong> (AssetImpairmentTestGenerate_JP)</p></li>
<li><p><strong>Generate asset impairment review</strong> (AssetImpairmentReviewGenerate_JP)</p></li>
<li><p><strong>Maintain the indicators for doing impairment review and test</strong> (AssetImpairmentIndicatorMaintain_JP)</p></li>
<li><p><strong>View the indicators for doing impairment review and test</strong> (AssetImpairmentIndicatorView_JP)</p></li>
<li><p><strong>Generate fixed asset impairment transaction report</strong> (AssetImpairmentTransactionGenerate_JP</p></li>
<li><p><strong>Generate journal line for asset impairment transactions</strong> (AssetImpairmentProposalGenerate_JP)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


