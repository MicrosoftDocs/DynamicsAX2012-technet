---
title: Fixed asset records
TOCTitle: Fixed asset records
ms:assetid: 5ea53226-d12a-466c-9bb8-cbd961cf6496
ms:mtpsurl: https://technet.microsoft.com/library/Dn527695(v=AX.60)
ms:contentKeyID: 59626230
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed assets
- asset
- fixed asset
- assets
- asset record
- asset records
- fixed asset records
- fixed assets record
- fixd asset record
- fixed assets records
audience: Application User
ms.search.region: Global
---

# Fixed asset records 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes the types of records that are kept for fixed assets, how you can view different types of information about fixed assets, and answers other common questions that you might have.

Each fixed asset is managed by using a set of records that include value models and depreciation books. A single asset can be associated with multiple value models and depreciation books. The financial dimension values that represent the legal entity that owns or controls the fixed asset are assigned to the asset on the value models.

## Where can I see the status of a fixed asset?

You can see the status of fixed assets in the **Value models** and **Depreciation books** forms. The fixed asset itself doesn’t have a status. The status is assigned individually to each value model and depreciation book that is assigned to the asset.

Each value model and depreciation book can have a different status. Value models and depreciation books that have an **Open** status are listed on the **Fixed assets acquired** list page. Value models and depreciation books that have not been acquired, or that have been acquired but do not have an **Open** status, are listed on the **Fixed assets not acquired** list page.

## Why does a fixed asset appear only one time on the Fixed assets list page, but multiple times on other fixed asset list pages?

The **Fixed assets** list page lists each fixed asset. The **Fixed assets acquired**, **Fixed assets not acquired**, and **Fixed assets sold or scrapped** list pages list the value models and depreciation books that are associated with the asset. Because one asset can be assigned to multiple value models and depreciation books, the same asset might be listed multiple times on those list pages.


> [!TIP]
> <P>From the pages that list all the value models, you can transfer a fixed asset by selecting any value model that is associated with the asset. When you do this, the asset transfer form lists all the value models that are associated with the asset, just as it does when you select an asset on the <STRONG>Fixed assets</STRONG> list page.</P>



## Where can I see which financial dimensions are associated with a depreciation book for a fixed asset?

The financial dimensions for a fixed asset are actually assigned to the value models, not to the depreciation books. You can see the financial dimensions for the value models in the **Value models** form.

## When I transfer a fixed asset, why can I use a blank value for one financial dimension and not for another financial dimension?

You can use a blank financial dimension value only if the dimension is configured to allow blank values in the chart of accounts.

## According to the Fixed asset transfer history form, an asset was transferred to a specific cost center and hasn’t been transferred again. But when I view the record of the fixed asset, the asset is in a different cost center. How did that happen?

When you update the **Default financial dimensions** values for a fixed asset in the **Value models** form, a transfer entry is not created or displayed in the **Transfer history** form.

The asset must have been transferred originally by using the **Transfer fixed assets** or **Mass transfer** form, and this is the record you see in the **Fixed asset transfer history** form. If the default financial dimensions for the asset were later changed by using the **Value models** form, there is no record of this change.


> [!NOTE]
> <P>In cumulative update 6 for Microsoft Dynamics AX 2012 or earlier versions, the <STRONG>Transfer fixed assets</STRONG> form is called <STRONG>Fixed asset transfer</STRONG>. The <STRONG>Mass transfer</STRONG> form is available only if cumulative update 7 for Microsoft Dynamics AX 2012 or a later version is installed.</P>



## When I create a fixed asset, why doesn’t it have the fixed asset number that I expect?

The fixed asset numbering for fixed asset groups and the general fixed asset numbering option in the **Fixed assets parameters** form are complementary. This means that fixed assets in a fixed asset group can have their own set of numbers, separate from the number sequence used for all of the other fixed assets. If no specific numbering exists for a fixed asset group, the default number sequence in the **Fixed assets parameters** form is used.

For more information about fixed asset numbers, see [Fixed asset number](https://technet.microsoft.com/library/aa618207\(v=ax.60\)) and [Fixed asset number sequence](https://technet.microsoft.com/library/aa500119\(v=ax.60\)).

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


