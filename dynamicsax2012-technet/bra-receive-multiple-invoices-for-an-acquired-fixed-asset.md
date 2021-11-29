---
title: (BRA) Receive multiple invoices for an acquired fixed asset
TOCTitle: (BRA) Receive multiple invoices for an acquired fixed asset
ms:assetid: 0941fc9a-4f4f-43da-822c-21795c6ec545
ms:mtpsurl: https://technet.microsoft.com/library/Dn305859(v=AX.60)
ms:contentKeyID: 54912959
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Receive multiple invoices for an acquired fixed asset 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When there is more than one invoice for the same fixed asset, the tax credit control must be applied to each combination of fixed asset and invoice. The combination will have its own control in terms of value and period, and the information is used to calculate fixed asset tax credit assessment in a future booking period.


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>



## Receive an additional invoice for an acquired fixed asset

When an additional invoice is received for an acquired fixed asset, the fixed asset record is updated.

1.  Create a purchase order for the fixed asset acquisition.

2.  On the purchase order, on the **Line details** FastTab, on the **Fixed assets** tab, select the fixed asset number and the value model, and then select **Acquisition** for the transaction type.
    
    The CIAP information will be saved on the fiscal document.

3.  Create and post a purchase invoice for the purchase order.

4.  When the booking process starts, the fiscal document that was previously created generates additional CIAP information for the booking period.

5.  To view CIAP fixed assets, click **Fiscal books** \> **Common** \> **All CIAP fixed assets**. Click **CIAP fixed asset** in the group on the **Action Pane**.

  


