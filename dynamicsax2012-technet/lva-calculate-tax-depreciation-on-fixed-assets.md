---
title: (LVA) Calculate tax depreciation on fixed assets
TOCTitle: (LVA) Calculate tax depreciation on fixed assets
ms:assetid: 1ba4adbc-8b6c-4d3b-869a-82325c8ecdc7
ms:mtpsurl: https://technet.microsoft.com/library/JJ910991(v=AX.60)
ms:contentKeyID: 52075317
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed assets
- calculate depreciation
- calculate tax depreciation
- tax depreciation
audience: Application User
ms.search.region: Latvia
---

# (LVA) Calculate tax depreciation on fixed assets 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In accordance with the Latvian legal requirements, the income tax for business organizations is adjusted using asset depreciation and is calculated using the tax depreciation method. You can calculate tax depreciation for an individual asset or for a category of fixed assets.

You must prepare and submit tax depreciation reports with your annual corporate income tax returns.

1.  Click **Fixed assets** \> **Periodic** \> **Tax depreciation**.

2.  Press CTRL+N to create a new calculation date for the tax depreciation.

3.  In the **Period name** field, enter a name for the tax depreciation for the specified calculation date.

4.  In the **Period status** field, select the period status for the calculation date.
    

    > [!NOTE]
    > <P>If the period status is set to <STRONG>Closed</STRONG>, you cannot reopen the period and recalculate the tax depreciation.</P>



5.  Click **Calculate** to calculate the tax depreciation for the value models that are selected in the **Category** field.
    

    > [!NOTE]
    > <P>Each asset is assigned a tax category. Depending on the type of asset, tax depreciation is calculated for each asset or for all items in the category as a group. As an example, if depreciation is calculated for a category, the calculation would be: the total tax net book value of the category at the beginning of the period, plus the total value of any new acquisitions and capital improvements in that category over the period, minus the total financial net book value of disposals in the category over the period, multiplied by the defined depreciation rate for the category.</P>



6.  You can click **Tax depreciation details** to view the calculation results.
    

    > [!NOTE]
    > <P>To view the results by tax categories, select a value model in the <STRONG>Category</STRONG> field. You can modify the calculation results, if necessary.</P>



## See also

[(LVA) Tax depreciation (form)](https://technet.microsoft.com/library/jj911011\(v=ax.60\))

[(LVA) Assign tax categories to fixed assets](lva-assign-tax-categories-to-fixed-assets.md)

[(LVA) Set up a value model for tax depreciation](lva-set-up-a-value-model-for-tax-depreciation.md)

  


