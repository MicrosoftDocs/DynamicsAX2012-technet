---
title: (RUS) Set up depreciation groups
TOCTitle: (RUS) Set up depreciation groups
ms:assetid: dc2feb13-c1da-4931-840d-67504e07bbd2
ms:mtpsurl: https://technet.microsoft.com/library/JJ711670(v=AX.60)
ms:contentKeyID: 49387992
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up depreciation groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Depreciation groups are defined for the value model for a fixed asset. Depreciation groups describe the depreciation profile, the service life, and the parameters for deferrals that are generated when a fixed asset is depreciated.

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Depreciation groups**.

2.  In the **Value model** field, select the value model that the depreciation group is defined for.

3.  Create a line.

4.  In the **Depreciation group** and **Name** fields, enter the depreciation group code and name for the depreciation group.

5.  In the **Depreciation method** field, select a depreciation method for the depreciation group.

6.  On the **General** FastTab, in the **Lifetime** field, enter the maximum service life, in years, during which depreciation is accrued for the fixed assets in the depreciation group.

7.  In the **Minimal depreciation** field, enter the minimum depreciation amount when you use the **Reducing remainder** depreciation method.

8.  In the **Depreciation start date** field, select the type of starting date for depreciation from the following options:
    
      - **From month when put into operation** – Depreciation is calculated from the first day of the month when the fixed asset is put to use after acquisition.
    
      - **Next month start** – Depreciation is calculated from the month after the fixed asset is put to use after acquisition.
    
      - **Next quarter start** – Depreciation is calculated from the quarter after the fixed asset is put to use after acquisition.
    
      - **Next half year start** – Depreciation is calculated from the half-year after the fixed asset is put to use after acquisition.
    
      - **Next year start** – Depreciation is calculated from the year after the fixed asset is put to use after acquisition.

9.  Click the **Deferrals** FastTab.

10. In the left pane, click **Disposal** to set up parameters to create deferrals on the disposal of fixed assets that accrue a loss. Click **Partial dismantlement** to create deferrals on the partial write-off of fixed assets that accrue a loss.
    

    > [!NOTE]
    > <P>When you create a transaction for the partial write-off or disposal of a fixed asset, if the transaction causes a loss, the transaction details are posted to a deferral account. This account contains the values of the calculated loss and the write-off time. The write-off time is calculated by using the fixed asset depreciation factor and the difference between the useful life of the depreciated asset and the actual period that the asset is used before disposal.</P>



11. In the right pane, press CTRL+N to create a line.

12. In the **Model number** field, select the model number of the deferral.

13. In the **Deferrals group** field, select the deferrals group for deferred expenses.

14. In the **Expense code** field, select the expense code for deferrals.

## See also

[(RUS) Depreciation groups (form)](https://technet.microsoft.com/library/jj678328\(v=ax.60\))

[(RUS) Fixed asset disposal](rus-fixed-asset-disposal.md)

  


