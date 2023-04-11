---
title: Set up consumption depreciation
TOCTitle: Set up consumption depreciation
ms:assetid: 96c94398-7dd5-4310-bd7b-399834782940
ms:mtpsurl: https://technet.microsoft.com/library/Aa498428(v=AX.60)
ms:contentKeyID: 36058643
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- consumption
- unit
- consumption depreciation
- consumption factor
- consumption unit
- factor
audience: Application User
ms.search.region: Global
---

# Set up consumption depreciation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To set up consumption depreciation, you must create consumption units and factors.

A consumption unit can be used as a reference for unit price entry for fixed assets and in the calculation of consumption depreciation proposals in the **Fixed assets** journal. A consumption factor is used to calculate depreciation proposals.

## To create consumption units

1.  Click **Fixed assets** \> **Setup** \> **Consumption** \> **Consumption units**.

2.  Click **New** to create a consumption unit, such as kilometer (km), kilogram (kg), or hour.

## To create consumption factors

1.  Click **Fixed assets** \> **Setup** \> **Consumption** \> **Consumption factors**.

2.  Click **New** to create a consumption factor.

3.  In the right pane, create an end date for each depreciation period.

4.  Determine whether to set up the consumption factor as a percentage or quantity, and enter values in the appropriate field.
    
    If you enter a percentage, the quantity estimated for the fixed asset in the **Estimated consumption** field in the **Value models** form is multiplied by the percentage set up for the period determined by the end date. This multiplied quantity is suggested as the depreciation quantity for the period.
    
    If you enter a quantity, the quantity set up for the period determined by the end date is suggested as the depreciation quantity for the consumption depreciation proposals.

## Assign consumption units and factors to fixed assets

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the fixed asset to set up consumption depreciation for.

3.  On the **Action Pane**, click **Value models** or **Depreciation books**.

4.  On the **Depreciation** tab, select values in the **Consumption factor** and **Unit** fields for the selected value model or depreciation book.
    

    > [!NOTE]
    > <P>If the fixed asset does not yet have a value model or depreciation book attached to it, you must select a value model or depreciation book for the fixed asset.</P>



5.  Enter values in the **Unit depreciation** and **Estimated consumption** fields. These fields are used when you run consumption depreciation proposals in journals.

## See also

[About consumption depreciation](about-consumption-depreciation.md)

[Consumption units (form)](https://technet.microsoft.com/library/aa576472\(v=ax.60\))

[Consumption factors (form)](https://technet.microsoft.com/library/aa571869\(v=ax.60\))

  


