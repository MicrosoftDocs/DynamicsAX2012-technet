---
title: (JPN) Set up reduction entry for fixed assets
TOCTitle: (JPN) Set up reduction entry for fixed assets
ms:assetid: 68f11d07-89ad-45bc-9552-0603f9d122af
ms:mtpsurl: https://technet.microsoft.com/library/Dn518244(v=AX.60)
ms:contentKeyID: 61223078
author: Khairunj
ms.date: 12/05/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.AssetPosting
- Forms.AssetDepBook
- Forms.AssetDisposalParameters
- disposal
- Forms.AssetBook
- Forms.AssetTable
- disposal parameters
- Japan
- Reduction entry
- Forms.AssetReductionEntryMassUpdate_JP
- Forms.AssetReductionEntryProfile_JP
- compressed book entries
- Compressed book entry
- Government subsidy
- reduction entry documents
- reduction entries
- reduction entry document
- MsDynAx060.Forms.AssetPosting
- MsDynAx060.Forms.AssetReductionEntryProfile_JP
- fixed asset posting profile
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up reduction entry for fixed assets 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you acquire a fixed asset using a government subsidy, the subsidy is treated as taxable revenue and can be registered in Microsoft Dynamics AX by using a reduction entry. You can use the following reduction entry methods to register the government subsidy for a fixed asset acquisition.

  - **Direct-off method** – The government subsidy amount is deducted directly from the acquisition cost of the fixed asset.

  - **Reserve method** – The government subsidy amount is maintained as a separate value on the equity side of the balance sheet. The government subsidy amount does not affect the net book value of the fixed asset.


> [!NOTE]
> <P>This topic has been updated for functionality that is included in Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



Follow the steps in this topic to set up a reduction entry document, and then assign the reduction entry document to a fixed asset or to multiple fixed assets. You can set up a fixed asset posting profile for reduction entry. You can also set up accounts for the transactions of type disposal. The transaction amounts are retrieved from these accounts when you post a fixed asset with reduction entry using the direct–off method.

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
<li><p>Ensure that you have set up basic fixed asset parameters, such as a default value model, reason codes, and number sequences, in the <strong>Fixed assets parameters</strong> form. For more information, see <a href="set-up-fixed-assets-parameters.md">Set up Fixed assets parameters</a>.</p></li>
<li><p>Define a fixed asset group in the <strong>Fixed asset groups</strong> form. For more information, see <a href="https://technet.microsoft.com/library/aa573347(v=ax.60)">Fixed asset groups (form)</a>.</p></li>
<li><p>Set up currencies and rounding rules to post depreciation amounts. For more information, see <a href="https://technet.microsoft.com/library/aa582902(v=ax.60)">Currencies (form)</a>.</p></li>
<li><p>Set up fixed asset locations in the <strong>Fixed assets locations</strong> form. For more information, see <a href="https://technet.microsoft.com/library/aa584400(v=ax.60)">Fixed assets locations (form)</a>.</p></li>
<li><p>Set up a fiscal calendar for depreciation and assign the calendar to a ledger. For more information, see <a href="key-tasks-fiscal-calendars-fiscal-years-and-periods.md">Key tasks: Fiscal calendars, fiscal years, and periods</a> and <a href="select-a-fiscal-calendar-for-a-ledger.md">Select a fiscal calendar for a ledger</a>.</p></li>
<li><p>Ensure that you have created a fixed asset record. For more information, see <a href="create-a-fixed-asset.md">Create a fixed asset</a>.</p></li>
<li><p>Ensure that you have set up a value model for the fixed asset in the <strong>Value models</strong> form. For more information, see <a href="set-up-value-models.md">Set up value models</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a reduction entry document

Use the **Reduction entry document** form to set up a reduction entry document that is used to identify the fixed assets that are eligible for subsidy.

To set up a reduction entry document, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Reduction entry documents**.

2.  Click **New** to create a document, and then specify the details about the document.
    
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
    <td><p><strong>Reduction entry document</strong></p></td>
    <td><p>Enter the name of the reduction entry document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reduction entry type</strong></p></td>
    <td><p>Select the reduction entry type for the document. You can select <strong>Direct-off</strong> or <strong>Reserve</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Depreciation convention</strong></p></td>
    <td><p>Select the depreciation convention to use for the reduction entry.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>None</strong> – The reduction entry is allocated in the same month as the month during which the government grant is claimed.</p></li>
    <li><p><strong>Full month</strong> – The reduction entry is allocated in the next month after the month during which the government grant is claimed.</p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Reserve</STRONG> in the <STRONG>Reduction entry type</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Subsidies reason</strong></p></td>
    <td><p>Enter the reason that the subsidies are claimed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Valid from</strong></p></td>
    <td><p>Enter the starting date of the period during which the document is effective and can be used for a fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Valid to</strong></p></td>
    <td><p>Enter the ending date of the period during which the document is effective and can be used for a fixed asset.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Max. amount</strong></p></td>
    <td><p>Enter a threshold amount for the subsidy.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Max. percentage rate</strong></p></td>
    <td><p>Enter the maximum percentage of the fixed asset’s acquisition cost that is allowed as a subsidy amount.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retention period</strong></p></td>
    <td><p>Specify the duration and the unit of time to use to calculate the minimum duration for which the asset must be used.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Repayment starts from</strong></p></td>
    <td><p>Select the starting date of the repayment period for the asset. You can select <strong>Acquisition date</strong>, <strong>Reduction entry claim date</strong>, or <strong>Ordinary depreciation start date</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Repayment type</strong></p></td>
    <td><p>Select the method to use to repay the subsidy. You can select <strong>Completely</strong>, <strong>Proportional</strong>, or <strong>Not required</strong>.</p></td>
    </tr>
    </tbody>
    </table>


## Optional: Assign a reduction entry document to a fixed asset

Use the **Fixed assets** form to assign a reduction entry document to a fixed asset. AX 2012 R2 uses the details of the reduction entry document that you assign to a fixed asset to calculate and post reduction entry amounts for the fixed asset.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Double-click the fixed asset that you have received the subsidy for, and then click **Edit**.

3.  On the **General** FastTab, in the **Reduction entry document** field, select the reduction entry document for the fixed asset.

4.  In the **Document date** field, select the date from which the document is effective.

When you update the reduction entry details for a fixed asset, the reduction entry details are updated for the value models and depreciation books that are associated with the fixed asset. You can modify the reduction entry details for a value model that is associated with a fixed asset in the **Reduction entry document** and **Document date** fields on the **General** tab in the **Value models** form. You can modify the reduction entry details for a depreciation book that is associated with a fixed asset in the **Reduction entry document** and **Document date** fields on the **General** tab in the **Depreciation books** form.

## Optional: Assign a reduction entry document to multiple fixed assets

Use the **Mass update for reduction entry document** form to assign a reduction entry document to multiple fixed assets. AX 2012 R2 uses the details of the reduction entry document that you assign to the fixed assets to calculate and post reduction entry amounts for the fixed assets.

1.  Click **Fixed assets** \> **Periodic** \> **Reduction entry document mass update**.

2.  Click **New** to create a line.

3.  In the **Fixed asset number** field, manually select the fixed assets to assign the reduction entry document to. Alternatively, you can click **Select fixed assets** to open the **Select criteria to pick up the candidates fixed asset into pools** form, where you can create an inquiry to filter the fixed assets to assign the reduction entry document to.

4.  Click **Assign reduction entry document**.

5.  In the **Document ID** field, select the reduction entry document to assign to the fixed assets.

6.  In the **Assign to lines** field, specify what fixed assets to assign the reduction entry document type to. Use the following table to decide what fixed assets to assign the selected document to.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Consideration</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>All lines</strong></p></td>
    <td><p>Select this option to assign the reduction entry document to all of the fixed assets in the <strong>Mass update for reduction entry document</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Lines without a reduction entry document</strong></p></td>
    <td><p>Select this option to assign the reduction entry document to all of the fixed assets in the <strong>Mass update for reduction entry document</strong> form that do not have a reduction entry certificate assigned.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Selected lines</strong></p></td>
    <td><p>Select this option to assign the reduction entry document only to the fixed assets that you selected in the <strong>Mass update for reduction entry document</strong> form.</p></td>
    </tr>
    </tbody>
    </table>


7.  Click **Assign**.

## 2\. Set up a fixed asset posting profile for reduction entry

Use the **Fixed asset posting profiles** form to set up a posting profile for reduction entry. You can also set up a posting profile to depreciate the asset that is applied with a reduction entry.

To set up the fixed asset posting profile for reduction entry, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**.

2.  Click **New** to create a fixed asset posting profile.

3.  In the **Posting profile** and **Description** fields, enter a name and a description for the posting profile.

4.  On the **Ledger accounts** FastTab, specify the details of the posting profile to use for the fixed asset. For more information, see [Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md).

5.  On the **Reduction entry** FastTab, select the **Direct-off** check box to specify the grouping level, main account, and offset account to post reduction entry transactions that use the direct-off method.

6.  Click **Add**, and then in the **Groupings** field, select the grouping level to set up a main account to post reduction entry transactions to. Use the following table to decide what grouping level to use.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Consideration</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Table</strong></p></td>
    <td><p>Select this option to select a main account for each fixed asset.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Group</strong></p></td>
    <td><p>Select this option to select a main account for each fixed asset group.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>All</strong></p></td>
    <td><p>Select this option to select a main account for all of the fixed assets.</p></td>
    </tr>
    </tbody>
    </table>


7.  In the **Fixed asset number** field, select a fixed asset or a fixed asset group for the reduction entry transactions. The values in this field are determined by the selection in the **Groupings** field.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Groupings</STRONG> field.</P>



8.  In the **Main account** and **Offset account** fields, select the default main account and the default offset account that the reduction entry transactions are posted to.

9.  Select the **Reserve** check box, and then repeat steps 6 through 8 to specify the grouping level, main account, and offset account to post reduction entry transactions that use the reserve method.

10. Select the **Allocation** check box, and then repeat steps 6 through 8 to specify the grouping level, main account, and offset account to post reduction entry allocation transactions.

## 3\. Set up disposal parameters for fixed assets with a transaction type of reduction entry using direct off method

To set up the disposal parameters for fixed assets with a transaction type of reduction entry using the direct-off method, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**. Click **Disposal** \> **Sale** or **Scrap**.

2.  On the **Disposal parameters by document type** FastTab, click **New**.

3.  In the **Value model** field, select a value model to apply to the reduction entry transaction type.

4.  In the **Post value** field, select one of the following options:
    
      - **Reduction entry - direct-off (prior years)** – To retrieve the amount that was posted for reduction entry during prior years.
    
      - **Reduction entry - direct-off (this year)** – To retrieve the amount that was posted for reduction entry during the present year.

5.  In the **Main account** and **Offset account** fields, select the main account and the offset account from which Microsoft Dynamics AX retrieves the transaction amount. For more information, see [About fixed asset disposal](about-fixed-asset-disposal.md) and [Disposal parameters (form)](https://technet.microsoft.com/library/aa499154\(v=ax.60\)).

## Next step

You have finished setting up a reduction entry for fixed assets. You can now apply the reduction entry and depreciate the fixed assets. For more information, see [(JPN) Apply reduction entry and depreciate fixed assets](jpn-apply-reduction-entry-and-depreciate-fixed-assets.md).

## Related tasks

[Fixed asset transaction types](fixed-asset-transaction-types.md)

[Basic setup of Fixed assets](basic-setup-of-fixed-assets.md)

[Fixed asset inquiries](fixed-asset-inquiries.md)

[Fixed asset posting and journals](fixed-asset-posting-and-journals.md)

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
</tbody>
</table>

  


