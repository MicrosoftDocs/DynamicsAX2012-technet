---
title: (JPN) Asset retirement obligation for fixed assets
TOCTitle: (JPN) Asset retirement obligation for fixed assets
ms:assetid: 6c8a91fb-481a-442a-b18e-e1b288ffc8f4
ms:mtpsurl: https://technet.microsoft.com/library/Dn479199(v=AX.60)
ms:contentKeyID: 59633805
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Fixed asset
- fixed asset journal
- fixed asset journals
- Japan
- Forms.AssetRetirementObligation_JP
- Asset retirement obligation
- Retirement
- MsDynAx060.Forms.AssetRetirementObligation_JP
audience: Application User
ms.search.region: Japan
---

# (JPN) Asset retirement obligation for fixed assets 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use Microsoft Dynamics AX to apply asset retirement obligation (ARO) to a tangible fixed asset when you acquire or construct the asset. ARO is used to estimate the costs that are related to the future disposal of an asset.

You can perform the following tasks by using ARO:

  - Specify the ARO type to use for the asset and the frequency at which the changes to the ARO amounts are posted.

  - Set up a discount rate schedule that uses current market discount rates that you specify to calculate the current value of the ARO.

  - Set up an estimated retirement cost plan for the asset retirement obligation and simulate ARO amounts for each fiscal period.

  - Adjust ARO amounts up or down to calculate interest expenses in case there are changes in the estimated retirement cost for the fixed asset. When you adjust ARO amounts upward, Microsoft Dynamics AX uses the new interest rate, if it is available. When you adjust ARO amounts downward, Microsoft Dynamics AX uses the old interest rate.

You can then apply the asset retirement obligation amounts when you depreciate or retire the fixed asset.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## How do I assign ARO to a fixed asset?

You must first create a document that contains details about the purpose of the ARO and the frequency at which the ARO is recognized and posted. You can specify whether to post ARO amounts yearly or quarterly. After you create the ARO document you can use the **Asset retirement obligation** form to attach the document to a fixed asset by assigning the value model of the asset to the ARO document. For more information, see [(JPN) Set up asset retirement obligation for fixed assets](jpn-set-up-asset-retirement-obligation-for-fixed-assets.md).

## How can I use the estimated retirement cost plan?

When a fixed asset is retired, your legal entity incurs a retirement cost. You can use the estimated retirement cost plan in Microsoft Dynamics AX to estimate and display the retirement cost at the time when it is incurred. The estimated retirement cost plan uses the market discount rate that you specify to calculate the retirement cost at the time when it is posted. This ensures that the retirement cost is properly distributed throughout the useful life of the fixed asset.

You can use the **Asset retirement obligation** form to create or modify an estimated cost retirement plan for a fixed asset that is assigned using ARO.

## Can I generate a proposal for an accretion expense?

An accretion expense is an interest expense that is incurred by a fixed asset at the end of each period of its useful life. To associate this interest expense with the ARO and post the expense amounts, you can generate a proposal to register the amounts that relate to the interest expense. You must do this so that the posted interest expense amounts are updated in the estimated retirement cost plan for the fixed asset.

Click **Proposals** \> **Asset retirement obligation - accretion expense** in the **Journal voucher** form to generate a proposal for an accretion expense.

If there is a significant change in the estimated retirement cost or discounted rate, you can adjust the retirement cost or discounted rate by clicking **Upward** or **Downward**, and then entering the adjustment amount in the **Upward** or **Downward** field in the **Asset retirement obligation** form. When you adjust ARO amounts upward, Microsoft Dynamics AX uses the new interest rate if it is available. When you adjust ARO amounts downward, Microsoft Dynamics AX uses the old interest rate.

## How and when can I apply capitalized ARO to fixed assets?

You can apply capitalized ARO to a fixed asset when you acquire a fixed asset or after you acquire the fixed asset. You can apply capitalized ARO to a fixed asset after acquisition when you perform upward or downward adjustment on the estimated retirement cost of the asset. You can generate a proposal to register the adjustment that is made to the fixed asset by clicking **Proposals** \> **Capitalized asset retirement obligation** in the **Journal voucher** form.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(JPN) Set up asset retirement obligation for fixed assets](jpn-set-up-asset-retirement-obligation-for-fixed-assets.md)

[(JPN) Depreciate and retire a fixed asset with asset retirement obligation](jpn-depreciate-and-retire-a-fixed-asset-with-asset-retirement-obligation.md)

[(JPN) Fixed asset depreciation](jpn-fixed-asset-depreciation.md)

  


