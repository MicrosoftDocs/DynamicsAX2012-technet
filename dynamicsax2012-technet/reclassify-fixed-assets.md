---
title: Reclassify fixed assets
TOCTitle: Reclassify fixed assets
ms:assetid: c2196535-0094-4823-94a1-341daff7cc89
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550705(v=AX.60)
ms:contentKeyID: 36059277
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Reclassify fixed assets [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To reclassify a fixed asset, you must transfer it to a new fixed asset group or assign a new fixed asset number to it in the same group.

## Reclassify fixed assets

1.  Click **Fixed assets** \> **Periodic** \> **Reclassification**.

2.  In the **Fixed asset group** and **Fixed asset number** fields, select the group and number of an existing fixed asset to reclassify.

3.  In the **New fixed asset group** field, select a group to transfer the fixed asset to. If the new fixed asset group is attached to a number sequence, the **New fixed asset number** field is updated with the number from the new fixed asset group number sequence. Otherwise, the **New fixed asset number** field is updated with the number from the number sequence that is set up in the **Fixed asset parameters** form. If a number sequence is not set up in the **Fixed asset parameters** form, enter a number in the **New fixed asset number** field.

4.  In the **Reclassification date** field, select the date of the transaction.

5.  In the **Number sequence code** field, select a number sequence code for the fixed asset transactions.

6.  Click **OK**.

## Results of reclassifying assets

  - All value models for the existing fixed asset are created for the new fixed asset. Any information that was set up for the original fixed asset is copied to the new fixed asset. The status of the value models for the original fixed asset is **Closed**.

  - The new value models of the new fixed asset contain the date of the reclassification in the **Acquisition date** field. The date in the **Depreciation run date** field is copied from the original asset information. If the depreciation has already started, the **Date when depreciation was last run** field displays the date of the reclassification.

  - The existing fixed asset transactions for the original fixed asset are canceled and regenerated for the new fixed asset.

## See also

[Reclassification (form)](https://technet.microsoft.com/en-us/library/aa573066\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

