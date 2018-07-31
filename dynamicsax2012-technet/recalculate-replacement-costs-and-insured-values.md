---
title: Recalculate replacement costs and insured values
TOCTitle: Recalculate replacement costs and insured values
ms:assetid: a8624c7e-a616-479e-9d78-0b135aac0ca0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243062(v=AX.60)
ms:contentKeyID: 39519270
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- asset replacement
- replacement costs
audience: Application User
ms.search.region: Global
---

# Recalculate replacement costs and insured values 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To recalculate replacement costs and insured values for fixed assets, you must first specify the percentage by which to change the existing costs and values. Then use the **Update replacement costs and insured values** form to recalculate the values. For more information, see [About recalculating replacement costs and insured values for fixed asset groups](about-recalculating-replacement-costs-and-insured-values-for-fixed-asset-groups.md).

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset groups**.

2.  Select the group that includes the fixed assets to update.

3.  Click the **General** FastTab.

4.  In the **Replacement cost factor** field, enter the replacement cost percentage. In the **Insured value factor** field, enter the insured value percentage.

5.  Repeat steps 2 through 4 for each group that includes fixed assets for which replacement costs and insured values must be recalculated.

6.  Click **Fixed assets** \> **Periodic** \> **Update replacement costs and insured values**.

7.  Click **Select** to specify the criteria that will be used to select assets. Click **OK** to perform the update.

## Results of the update

  - In the **Fixed assets** form, the values in the **Insured value** and **Replacement cost** fields are recalculated for all fixed assets that have a status of **Open**, and that meet the selection criteria.

  - In the **Fixed assets** form, the current date is displayed in the **Last periodic value/cost update** field on the **Insurance** FastTab.

## See also

[About recalculating replacement costs and insured values for fixed asset groups](about-recalculating-replacement-costs-and-insured-values-for-fixed-asset-groups.md)

[Update replacement costs and insured values (form)](https://technet.microsoft.com/en-us/library/hh227488\(v=ax.60\))

  


