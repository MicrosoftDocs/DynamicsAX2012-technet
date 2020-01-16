---
title: About bonus depreciation
TOCTitle: About bonus depreciation
ms:assetid: 6a2ad77a-0642-4b72-a3de-4daf5bb411aa
ms:mtpsurl: https://technet.microsoft.com/library/Aa571174(v=AX.60)
ms:contentKeyID: 36057977
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation
- fixed asset depreciation
- bonus depreciation
- fixed asset bonus depreciation
audience: Application User
ms.search.region: Global
---

# About bonus depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

With bonus depreciation, you can take extra or bonus depreciation amounts during the first year that the asset is put in service and depreciated. Bonus depreciation is available only for depreciation books, not value models, and it is always taken before any other depreciation calculations.

You can calculate bonus depreciation by using the proposal process, or you can create manual bonus depreciation transactions. You cannot create bonus depreciation transactions if depreciation transactions or depreciation adjustment transactions exist for that asset depreciation book.

When you use the proposal process to calculate bonus depreciation, all existing bonus transactions are included in the calculation of the basis. The calculation also includes any previous bonus depreciations that you entered manually for the asset.

If more than one bonus depreciation will be taken for an asset, the priority will be considered. Each bonus reduces the asset basis for the next bonus. Salvage value is not considered in the asset basis for bonus depreciation calculations, and the depreciation convention does not apply for bonus depreciation.

Currently in the United States, certain property qualifies as Section 179 property. By using the Section 179 deduction, you can recover all or part of the cost of certain property, up to a limit. You can recover the cost by deducting it in the year in which you place the property in service.

## Example

The following bonus depreciations are associated with an asset depreciation book:

Section 179: 1,000.00, Priority 1

Liberty Zone: 30 percent, Priority 2

The asset acquisition cost is 5,000.00. When bonus depreciation is calculated, the first bonus depreciation amount will be 1,000.00 for the Section 179 depreciation.

The next bonus depreciation amount, for the Liberty Zone depreciation, will be calculated as follows:

Acquisition cost – 1,000 (Section 179 depreciation) x 30% = 1,200

If the bonus depreciation amount is more than the remaining acquisition cost, the bonus depreciation amount will be either the result of the bonus depreciation calculation or the remaining acquisition cost, whichever is less.

If the remaining acquisition cost is zero or less, bonus depreciation transactions will not be generated.

When bonus depreciation is calculated using the proposal process, a bonus depreciation transaction will be created for all applicable bonus depreciation records that are associated with the asset depreciation book.

When book depreciation transactions are derived from a value model, bonus depreciation will not be generated automatically. Bonus depreciations are not supported by value models.

You can create an unlimited number of bonus depreciation records. After you assign them to the asset group depreciation book, they will be applied to the asset depreciation book.

Bonus depreciation is entered as either a percentage or a fixed amount. When you post depreciation proposals, bonus depreciation transactions will be posted to the depreciation book as separate transactions from the depreciation transactions.

## See also

[Set up bonus depreciation](set-up-bonus-depreciation.md)

  


