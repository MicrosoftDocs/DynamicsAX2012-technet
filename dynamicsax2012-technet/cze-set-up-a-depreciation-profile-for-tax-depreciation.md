---
title: (CZE) Set up a depreciation profile for tax depreciation
TOCTitle: (CZE) Set up a depreciation profile for tax depreciation
ms:assetid: 11f7101d-bb5d-4a9b-a426-5aee52e31f24
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677458(v=AX.60)
ms:contentKeyID: 49384762
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Set up a depreciation profile for tax depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up or modify a depreciation profile that contains the calculations that are used to evaluate the reduction in value of depreciable assets over time.

1.  Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation profiles**.

2.  In the **Depreciation profiles** form, click **New**, and then in the **Depreciation profile** field, enter the name of the profile.

3.  In the **Method** field, select the depreciation method.
    
    For more information, see [Depreciation methods and conventions](depreciation-methods-and-conventions.md).

4.  In the **Depreciation year** field, select the type of depreciation year:
    
      - **Calendar** – The end of the depreciation period is equal to the end of the calendar year.
    
      - **Fiscal** – The end of the depreciation period is equal to the end of the current fiscal period.

5.  In the **Period frequency** field, select the frequency of ledger accruals during the calendar or fiscal year.
    
    The options that are available are based on the option that you selected in the **Depreciation year** field.

6.  Select the **Full depreciation** check box to fully depreciate the fixed asset when the remaining service life is zero.

  


