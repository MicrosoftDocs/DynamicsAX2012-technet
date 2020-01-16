---
title: (JPN) Reduction entry for fixed assets
TOCTitle: (JPN) Reduction entry for fixed assets
ms:assetid: 24566bcf-b8e7-433f-805e-02756f08d989
ms:mtpsurl: https://technet.microsoft.com/library/Dn518218(v=AX.60)
ms:contentKeyID: 60434949
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation
- fixed assets
- fixed asset
- Japan
- Direct-off method
- Reserve method
- government subsidies
- government subsidy
- Reduction entry
- subsidies
- subsidy
audience: Application User
ms.search.region: Japan
---

# (JPN) Reduction entry for fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you acquire a fixed asset using a government subsidy, the subsidy is treated as taxable revenue. You can use the following reduction entry methods to record the government subsidy for a fixed asset acquisition:

  - **Direct-off method** – The government subsidy amount is deducted directly from the acquisition cost of the fixed asset.

  - **Reserve method** – The government subsidy amount is maintained as a separate value on the equity side of the balance sheet. The government subsidy amount does not affect the net book value of the fixed asset.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



If you calculate depreciation for a fixed asset that you acquire using the subsidy, Microsoft Dynamics AX adjusts the calculations for depreciation and threshold depending on the subsidy for the fixed asset.

## What is a reduction entry document?

A reduction entry document is a document that you can attach to a fixed asset that is sponsored using a government subsidy. The reduction entry certificate contains the details about the government subsidy, such as the reduction entry method, depreciation convention, reason, validity, and subsidy threshold. AX 2012 R2 uses the details of the reduction entry document to calculate and post reduction entry amounts.

## How can I use reduction entry for fixed assets in AX 2012 R2?

You can perform the following tasks to use reduction entry for fixed asset acquisition:

  - Set up a reduction entry document that is used to identify the fixed assets that are eligible for subsidy.

  - Assign a reduction entry document to a fixed asset. Alternatively, you can assign a reduction entry document to multiple fixed assets.

  - Set up a fixed asset posting profile for a reduction entry.

  - Create and post a fixed asset journal by specifying the reduction entry details.

  - Create and post a purchase order to use the subsidy for additional fixed asset acquisitions.

  - When you run a depreciation proposal, AX 2012 R2 automatically calculates and posts the allocation of reduction entry along with the depreciation process.

  - Set up and run a batch process to assign the reduction entry documents to fixed assets periodically by specifying the criteria, such as fixed asset groups and periods.

  - If claiming a government grant after acquiring fixed assets is required, you can generate a reduction entry proposal for fixed assets by attaching the reduction entry document to the proposal.

## How and when can I apply reduction entry to a fixed asset?

You can apply reduction entry to a fixed asset that is eligible for government subsidy. You can use the direct-off method to set up AX 2012 R2 to deduct the government subsidy amount directly from the acquisition cost of the fixed asset. Alternatively, you can use the reserve method to maintain the government subsidy as a separate value on the equity side of the balance sheet. The government subsidy amount does not affect the net book value of the fixed asset.

## Can I apply the same reduction entry document to more than one fixed asset?

Yes. You can use the **Mass update for reduction entry document** form to assign a reduction entry document to multiple fixed assets.

## Can I attach a reduction entry document to a fixed asset that is acquired by using a purchase order?

Yes. You can attach a reduction entry document to a fixed asset. When you create and post a purchase order to acquire the fixed asset, the subsidy amount is posted automatically.

## Can I generate a report that can be used to review the details of reduction entry transactions?

Yes. You can generate the **Reduction entry transaction summary** report that contains details about the reduction entry transactions based on the criteria that you specify, such as fiscal year, reduction entry method, and book type.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(JPN) Set up reduction entry for fixed assets](jpn-set-up-reduction-entry-for-fixed-assets.md)

[(JPN) Apply reduction entry and depreciate fixed assets](jpn-apply-reduction-entry-and-depreciate-fixed-assets.md)

  


