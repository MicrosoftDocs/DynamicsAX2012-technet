---
title: (JPN) Generate Fixed assets reports
TOCTitle: (JPN) Generate Fixed assets reports
ms:assetid: 8b0e06b3-a875-45df-af26-ab702374fc47
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn636900(v=AX.60)
ms:contentKeyID: 61223080
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- generate reports
- SSRS_Reports.Reports.AssetCorpTaxActAppendedTables_JP
- SSRS_Reports.Reports.AssetDepreciableAssets_JP
- Appended Table report
- Appended Table reports
- SSRS.Reports.Reports.AssetCorpTaxActAppendedTable6_JP
- generate report
- fixed asset report
- fixed asset reports
- SSRS.Reports.Reports.AssetCorpTaxActAppendedTable7_JP
- SSRS.Reports.Reports.AssetCorpTaxActAppendedTable8_JP
---

# (JPN) Generate Fixed assets reports [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to generate detailed reports about depreciated fixed assets. The details that are displayed in the report depend on the depreciation method that you use to depreciate the fixed asset, and whether the fixed asset has increased or decreased in net value.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



You can generate the following reports for fixed assets annually.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name of the report</p></th>
<th><p>Classification of assets</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Appended Table No.16 (1)</strong></p></td>
<td><p>This report contains information about the amortization calculation of depreciable assets using the new straight line method or the old straight line method.</p></td>
</tr>
<tr class="even">
<td><p><strong>Appended Table No. 16 (2)</strong></p></td>
<td><p>This report contains information about the amortization calculation of depreciable assets using the 200% or 250% declining balance method or the old declining balance method.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Appended Table No. 16 (6)</strong></p></td>
<td><p>In AX 2012 R3: This report contains information about the amortization calculation of deferred, assets using the equally divided depreciation method or by specifying depreciation amounts manually for each fiscal period.</p></td>
</tr>
<tr class="even">
<td><p><strong>Appended Table No. 16 (7)</strong></p></td>
<td><p>In AX 2012 R3: This report contains information about the amortization calculation of low value assets using the equally divided depreciation method or by specifying depreciation amounts manually for each fiscal period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Appended Table No. 16 (8)</strong></p></td>
<td><p>In AX 2012 R3: This report contains information about the amortization calculation of lump-sum value assets using the equally divided depreciation method or by specifying depreciation amounts manually for each fiscal period.</p></td>
</tr>
<tr class="even">
<td><p><strong>No. 26 Form depreciable asset</strong></p></td>
<td><p>This report contains details about all of the transactions for depreciable fixed assets with an increased or decreased net value.</p></td>
</tr>
<tr class="odd">
<td><p><strong>No. 26 Form Appended Table 1</strong></p></td>
<td><p>This report contains details about the transactions that increase the value of depreciable fixed assets. These transactions can be acquisitions, acquisition adjustments, revaluations that increase the value of fixed assets, or write-up adjustments.</p></td>
</tr>
<tr class="even">
<td><p><strong>No. 26 Form Appended Table 2</strong></p></td>
<td><p>This report contains details about the transactions that decrease the value of depreciable fixed assets. These transactions can be fixed asset disposals, revaluations that decrease the value of fixed assets, or write-down adjustments.</p></td>
</tr>
</tbody>
</table>


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
<td><p>Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Japan</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up the parameters to calculate the depreciation for the fixed assets. For more information, see <a href="set-up-fixed-assets-parameters.md">Set up Fixed assets parameters</a>.</p></li>
<li><p>Set up depreciation methods. For more information, see <a href="jpn-set-up-depreciation-and-depreciation-methods.md">(JPN) Set up depreciation and depreciation methods</a>.</p></li>
<li><p>Calculate fixed asset depreciation. For more information, see <a href="jpn-configure-and-calculate-fixed-asset-depreciation.md">(JPN) Configure and calculate fixed asset depreciation</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Generate the Appended Table No. 16 reports

Depending on the version that you are using, you can use the following forms to generate the Appended Table No.16 reports.

  - In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: **Appended table 1** – Generate the Appended Table No. 16 (1) report.

  - In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: **Appended table 2** – Generate the Appended Table No. 16 (2) report.

  - In AX 2012 R3: **Appended table 6** – Generate the Appended Table No. 16 (6) report.

  - In AX 2012 R3: **Appended table 7** – Generate the Appended Table No. 16 (7) report.

  - In AX 2012 R3: **Appended table 8** – Generate the Appended Table No. 16 (8) report.

To generate the Appended Table No. 16 reports, follow these steps.

1.  Click **Fixed assets** \> **Reports** \> **External** \> **Corporate tax return for report series 16** \> **Appended table 1**.
    
    –or–
    
    Click **Fixed assets** \> **Reports** \> **External** \> **Corporate tax return for report series 16** \> **Appended table 2**.
    
    –or–
    
    In AX 2012 R3: Click **Fixed assets** \> **Reports** \> **External** \> **Corporate tax return for report series 16** \> **Appended table 6**.
    
    –or–
    
    In AX 2012 R3: Click **Fixed assets** \> **Reports** \> **External** \> **Corporate tax return for report series 16** \> **Appended table 7**.
    
    –or–
    
    In AX 2012 R3: Click **Fixed assets** \> **Reports** \> **External** \> **Corporate tax return for report series 16** \> **Appended table 8**.

2.  In the **Fiscal year** field, select the tax declaration year to generate the report for.

3.  Click **Select**, and then specify the following additional criteria to select fixed asset transactions for the report.
    
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
    <td><p><strong>Major type</strong></p></td>
    <td><p>The top-level classification of the asset, such as equipment, buildings, land, infrastructure, or utilities.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Fixed asset number</strong></p></td>
    <td><p>The identification number of the fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Value model</strong></p></td>
    <td><p>The value model of the fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Property group</strong></p></td>
    <td><p>The property group of the fixed asset.</p></td>
    </tr>
    </tbody>
    </table>


4.  Click **OK** to close the form, and then click **OK** to generate the report.

## 2\. Generate the No. 26 Form depreciable asset report

You can use the **Form 26 - Depreciable assets** form to generate the No. 26 Form depreciable asset report. This report contains details about the fixed assets that have increased or decreased in net value for a calendar year that you specify.

To generate the No. 26 Form depreciable asset report, follow these steps.

1.  Click **Fixed assets** \> **Reports** \> **External** \> **Form 26 - Depreciable assets**.

2.  In the **Calendar year** field, select the calendar year to generate the report for.

3.  In the **Prefecture** field, select the prefecture or state where the fixed asset is located.

4.  In the **City** field, select the city or ward where the fixed asset is located.

5.  Select the **Blue tax return** check box to indicate that your legal entity files blue form tax returns.

6.  Select the **Nontaxable** check box to include fixed assets for which depreciation tax is not applicable.

7.  In the **Office building asset number** field, select the identification number of your legal entity’s office building.

8.  Click **Select**, and then specify the following additional criteria to select fixed asset transactions for the report.
    
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
    <td><p>The fixed asset group.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Major type</strong></p></td>
    <td><p>The top-level classification of the asset, such as equipment, buildings, land, infrastructure, or utilities.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fixed asset number</strong></p></td>
    <td><p>The identification number of the fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value model</strong></p></td>
    <td><p>The value model of the fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Posting layer</strong></p></td>
    <td><p>The posting layer that the fixed asset transactions are posted to.</p></td>
    </tr>
    </tbody>
    </table>


9.  Click **OK** to close the form, and then click **OK** to generate the report.

## 3\. Generate the No. 26 Form Appended Table 1 and No. 26 Form Appended Table 2 reports

You can use the **Form 26 - Depreciable assets - Appended table 1** and **Form 26 - Depreciable assets - Appended table 2** forms to generate the No. 26 Form Appended Table 1 and No. 26 Form Appended Table 2 reports.


> [!NOTE]
> <P>You can also select the <STRONG>Print appended table 1 and table 2</STRONG> check box in the <STRONG>Form 26 - Depreciable assets</STRONG> form to generate the reports along with the No. 26 Form depreciable asset report.</P>



To generate the No. 26 Form Appended Table 1 and No. 26 Form Appended Table 2 reports, follow these steps.

1.  Click **Fixed assets** \> **Reports** \> **External** \> **Form 26 - Depreciable assets - Appended table 1**.
    
    –or–
    
    Click **Fixed assets** \> **Reports** \> **External** \> **Form 26 - Depreciable assets - Appended table 2**.

2.  In the **Calendar year** field, select the calendar year to generate the report for.

3.  In the **Prefecture** field, select the prefecture or state where the fixed asset is located.

4.  In the **City** field, select the city or ward where the fixed asset is located.

5.  Click **Select**, and then specify the following additional criteria to select the fixed asset transactions for the report.
    
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
    <td><p>The fixed asset group.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Major type</strong></p></td>
    <td><p>The top-level classification of the asset, such as equipment, buildings, land, infrastructure, or utilities.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fixed asset number</strong></p></td>
    <td><p>The identification number of the fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value model</strong></p></td>
    <td><p>The value model of the fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Posting layer</strong></p></td>
    <td><p>The posting layer that the fixed asset transactions are posted to.</p></td>
    </tr>
    </tbody>
    </table>


6.  Click **OK** to close the form, and then click **OK** to generate the report.

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
<td><p>To perform this task, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Inquire into fixed assets</strong> (AssetFixedAssetsInquire)</p></li>
<li><p><strong>Review fixed assets process performance</strong> (AssetFixedAssetsProcessPerfReview)</p></li>
<li><p><strong>Inquire into fixed asset transaction status</strong> (AssetFixedAssetTransactionStatusInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the <strong>Generate fixed asset reports for Japan</strong> (AssetReportsGenerate_JP) privilege.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

