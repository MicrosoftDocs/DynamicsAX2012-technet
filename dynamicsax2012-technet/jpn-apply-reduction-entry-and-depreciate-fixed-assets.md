---
title: (JPN) Apply reduction entry and depreciate fixed assets
TOCTitle: (JPN) Apply reduction entry and depreciate fixed assets
ms:assetid: 3785b26c-222e-4f76-b0e0-625f01e3bb92
ms:mtpsurl: https://technet.microsoft.com/library/Dn518243(v=AX.60)
ms:contentKeyID: 61223079
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Classes.AssetDepBookProposalDepreciation
- depreciation
- Forms.SysOperationTemplateForm
- fixed assets
- Forms.AssetBookTable
- fixed asset
- Forms.PurchTable
- Forms.LedgerJournalTable
- Forms.AssetDepBookJournalTrans
- Forms.LedgerJournalTransAsset
- Forms.AssetDepBookJournalTable
- Japan
- government subsidy
- Reduction entry
- Compressed book entry
- Compressed book entries
- depreciate
- Reduction entries
- SSRS_Reports.Reports.AssetReductionEntryTransactionSummary_JP
- MsDynAx060.Forms.AssetBookTable
audience: Application User
ms.search.region: Japan
---

# (JPN) Apply reduction entry and depreciate fixed assets 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you set up a reduction entry for fixed assets, you can apply reduction entry to a fixed asset that is eligible for government subsidy. You can use the direct-off method to set up Microsoft Dynamics AX 2012 R2 to deduct the government subsidy amount directly from the acquisition cost of the fixed asset. Alternatively, you can use the reserve method to maintain the government subsidy as a separate value on the equity side of the balance sheet. The government subsidy amount does not affect the net book value of the fixed asset. For more information, see [(JPN) Reduction entry for fixed assets](jpn-reduction-entry-for-fixed-assets.md).

When you run a depreciation proposal, AX 2012 R2 automatically calculates and posts the allocation of the reduction entry along with the depreciation process.

Follow the steps in this topic to apply the reduction entry to a fixed asset, and then calculate depreciation for the fixed asset.


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
<td><p><strong>Reduction entry setup task</strong></p></td>
<td><p>Set up a reduction entry document, and then assign the reduction entry document to a fixed asset or to multiple fixed assets. Additionally, set up a fixed asset posting profile for a reduction entry.</p></td>
</tr>
</tbody>
</table>


## Create and post a fixed asset acquisition journal by specifying the reduction entry details

Use the **Fixed assets** and **Journal voucher** forms to create and post a fixed asset acquisition journal by specifying the reduction entry document type and the identification code of the reduction entry document. Alternatively, you can generate the reduction entry transaction for the fixed asset based on the reduction entry details that you specified for the fixed asset.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Select or create a fixed asset acquisition journal. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).

3.  Click **Lines**, and then select or create a fixed asset acquisition journal line. For more information, see [Journal voucher - Fixed assets (form)](https://technet.microsoft.com/library/aa620564\(v=ax.60\)).

4.  On the **Overview** tab, in the **Account** and **Value model** fields, select a fixed asset and value model to apply the reduction entry to.

5.  In the **Document type** field, select **Reduction entry - direct-off** or **Reduction entry - reserve** as the reduction entry method. In the **Document ID** field, select the identification code of the reduction entry document.
    
    Alternatively, click **Functions** \> **Generate transactions for reduction entry document** to create additional reduction entry lines for the fixed asset based on the reduction entry details that you specified for the fixed asset or value model. For more information, see “Optional: Assign a reduction entry certificate to a fixed asset” and “Optional: Assign reduction entry certificates to multiple fixed assets” in [(JPN) Set up reduction entry for fixed assets](jpn-set-up-reduction-entry-for-fixed-assets.md).

6.  In the **Debit** field, enter the subsidy amount.

7.  Click **Validate** \> **Validate** to validate the journal.

8.  Click **Post** \> **Post** to post the fixed asset acquisition by claiming the subsidy.

## Generate a reduction entry proposal

If claiming a government grant after acquiring fixed assets is required, you can use the **Reduction entry - proposal** form to generate a reduction entry proposal for fixed assets to which the reduction entry documents are assigned.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  In the **Fixed assets** form, create an acquisition journal for the reduction entry, and then click **Lines**.

3.  In the **Journal voucher** form, click **Proposals** \> **Reduction entry proposal**.

4.  In the **Reduction entry - proposal** form, click **Select** to open an inquiry, where you can specify the criteria, such as fixed asset number, fixed asset group, and value models for the assets to include in the proposal.

5.  Click **OK** to close the inquiry.

6.  In the **Reduction entry - proposal** form, click **OK** to generate transaction lines for the fixed assets that are eligible for the subsidy in the **Journal voucher** form.

7.  In the **Debit** field, enter the subsidy amount.

8.  Specify additional information for the reduction entry transaction, if required.

9.  Click **Validate** \> **Validate** to validate the journal.

10. Click **Post** \> **Post** to post the reduction entry amounts for fixed assets.

## Create and post a purchase order to acquire additional fixed assets by using a subsidy

Use the **Purchase order** and **Vendor invoice** forms to create and post a purchase order to acquire additional fixed assets by using a subsidy.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order**, enter the required information to create a purchase order, and then click **OK**. For more information, see [Create a purchase order](create-a-purchase-order.md).

3.  In the **Purchase order** form, on the **Line details** FastTab, on the **Fixed assets** tab, in the **Fixed asset number** field, select the fixed asset for which you have assigned the reduction entry details. For more information, see “Optional: Assign a reduction entry certificate to a fixed asset” and “Optional: Assign reduction entry certificates to multiple fixed assets” in [(JPN) Set up reduction entry for fixed assets](jpn-set-up-reduction-entry-for-fixed-assets.md).
    
    The identification of the reduction entry document and the subsidy amount for the fixed asset are updated in the **Reduction entry document** and **Reduction entry amount** fields.

4.  In the **Transaction type** field, select **Acquisition** or **Acquisition adjustment** as the type of fixed asset transaction.

5.  On the **Action Pane**, on the **Invoice** tab, click **Invoice** to open the **Vendor invoice** form.

6.  Verify the reduction entry details in the **Reduction entry document** and **Reduction entry amount** fields on the **Fixed assets** tab on the **Line details** FastTab.

7.  Post the purchase order for the fixed asset acquisition. The subsidy amount is posted automatically.

## Generate a depreciation proposal by allocating the reserve for reduction entry

Use the **Depreciation proposal** form to generate a depreciation proposal for fixed assets by allocating the reserve for a reduction entry. When you generate a depreciation proposal, AX 2012 R2 automatically calculates and posts the allocation of the reduction entry along with the depreciation process.

To perform this task, follow these steps:

1.  Click **Fixed assets** \> **Journals** \> **Depreciation book journal**.
    
    –or–
    
    Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Select or create a depreciation journal, and then click **Lines**. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)) and [Depreciation book journal (form)](https://technet.microsoft.com/library/aa634765\(v=ax.60\)).

3.  In the **Journal voucher** form or the **Journal line** form, enter the required details for the voucher. For more information, see [Journal voucher - Fixed assets (form)](https://technet.microsoft.com/library/aa620564\(v=ax.60\)) and [Journal line (form)](https://technet.microsoft.com/library/hh209722\(v=ax.60\)).

4.  Click **Proposals** \> **Depreciation proposal**.

5.  In the **Depreciation proposal** form, in the **To date** field, enter the ending date of the period to create the depreciation profile for.
    

    > [!NOTE]
    > <P>If required, you can select the <STRONG>Summarize depreciation</STRONG> check box to summarize the details of monthly depreciation amounts in one journal line.</P>



6.  Select the **Reduction entry allocation** check box to automatically calculate the allocation of the reduction entry along with the depreciation process.

7.  Click **Select** to specify additional criteria, such as fixed asset number and fixed asset group to generate the depreciation proposal. Click **OK**.

8.  In the **Depreciation proposal** form, click **OK** to generate the depreciation and reduction entry allocation lines in the **Journal voucher** form or the **Journal line** form.

9.  Validate and post the journal.

After you generate and post the depreciation for a fixed asset by allocating the reserve for a reduction entry, you can verify the information in the following fields on the **Reserve for reduction entry** tab in the **Profile** form:

  - **Pre-adjustment reduction entry amount** – The unadjusted reduction entry amount if the acquisition of the asset and the subsidy claim occur in the same fiscal year.

  - **Post-adjustment reduction entry amount** – The adjusted reduction entry amount if the subsidy is claimed in the fiscal year that occurs after the year of acquisition.

  - **Beginning balance of accumulated allocation of reserve for reduction entry** – The beginning balance of the accumulated allocation of reserve for the reduction entry.

  - **YTD allocation of reserve for reduction entry** – The total allocation of reserve for the reduction entry that is incurred from the beginning of the fiscal year of the selected date.

  - **Beginning balance of reduction entry** – The beginning balance of the reduction entry from the beginning of the year until the selected date.

  - **Allocation of reserve for reduction entry** – The allocation of the reserve for the reduction entry for the fiscal period for the selected date.

  - **YTD reduction entry balance** – The remaining value of the reduction entry.

You can also verify the revenue amount for the reserve method and the net balance after deducting the reserve subsidy from the acquisition cost in the **Reduction entry amount** and **Net balance** fields in the **Fixed asset balances** form.

## Generate a report to review the details of reduction entry transactions

Use the **Reduction entry transaction summary** form to generate the Reduction entry transaction summary report, which contains details about the reduction entry transactions based on the criteria that you specify, such as fiscal year, reduction entry method, and book type.

1.  Click **Fixed assets** \> **Reports** \> **Transactions** \> **Reduction entry transaction summary**.

2.  In the **Fiscal year** field, select the fiscal year to generate the report for.

3.  In the **Reduction entry type** field, select **Direct-off** or **Reserve** as the reduction entry type to generate the report for.

4.  In the **Book type** field, select **Value model** or **Depreciation book** as the book type to generate the report for.

5.  In the **View by** field, select **Reduction entry document view** or **Fixed asset group view** as the report view.

6.  Click **Select** to specify additional criteria, such as fixed asset number, fixed asset group, and book to generate the report. Click **OK**.

7.  In the **Reduction entry transaction summary** form, click **OK** to generate the report.

## Related tasks

[Fixed asset transaction types](fixed-asset-transaction-types.md)

[Basic setup of Fixed assets](basic-setup-of-fixed-assets.md)

[Fixed asset inquiries](fixed-asset-inquiries.md)

[Fixed asset posting and journals](fixed-asset-posting-and-journals.md)

[(JPN) Set up depreciation and depreciation methods](jpn-set-up-depreciation-and-depreciation-methods.md)

[(JPN) Fixed asset depreciation](jpn-fixed-asset-depreciation.md)

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
<li><p><strong>Maintain fixed asset transactions</strong> (AssetFixedAssetTransactionsMaintain)</p></li>
<li><p><strong>Maintain fixed assets</strong> (AssetFixedAssetsMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Security roles and privileges</p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p><strong>Reduction entry summary report</strong> (AssetReductionEntrySummaryReport_JP)</p></li>
<li><p><strong>View reduction entry profile</strong> (AssetViewReductionEntryProfile_JP)</p></li>
<li><p><strong>Create depreciation book reduction entry proposal</strong> (AssetCreateDepBookREProposal_JP)</p></li>
<li><p><strong>Create fixed asset reduction entry proposal</strong> (AssetCreateFixedAssetREProposal_JP)</p></li>
<li><p><strong>Maintain reduction entry profile</strong> (AssetMaintainReductionEntryProfile)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


