---
title: (BRA) Acquire a CIAP fixed asset
TOCTitle: (BRA) Acquire a CIAP fixed asset
ms:assetid: 7b22d295-1ce0-4286-a452-20d84839a316
ms:mtpsurl: https://technet.microsoft.com/library/Dn305873(v=AX.60)
ms:contentKeyID: 54912973
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- forms.FBCIAPAssetTable_BR
- MsDynAx060.forms.FBCIAPAssetTable_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Acquire a CIAP fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When a legal entity purchases a fixed asset, the ICMS tax on the transaction, which is included in the fixed asset price, can be refunded in 48 installments. The legal entity must present a specific fiscal book or report the information within the SPED fiscal file to the government. Create a Controle de Crédito de ICMS do Ativo Permanente (CIAP) fixed asset to track these installments.

To generate fixed asset tax credit, the legal entity must retain acquisition information for the fixed asset and the incoming invoices for a time period. This information is used for the fixed asset tax credit assessment in a future booking period.


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>



## Acquire a CIAP fixed asset

1.  Create a fixed asset in the **Fixed assets** form. For more information, see “Create fixed assets”.

2.  On **Fixed assets** form, on the **Fiscal information** FastTab, select the **ICMS credit** check box.

3.  Enter the number of installments in the **ICMS credit installments** field.

4.  Select the fiscal establishment ID for the fixed asset.

5.  Create a purchase order for the fixed asset acquisition.

6.  On the purchase order, on the **Line details** FastTab, on the **Fixed assets** tab, select the fixed asset number and the value model, and then select **Acquisition** for the transaction type.
    
    The CIAP information will be saved on the fiscal document.

7.  Create and post a purchase invoice for the purchase order.
    
    When the booking period is created, the fiscal document will be processed and a CIAP fixed asset will be created.

8.  To view CIAP fixed assets, click **Fiscal books** \> **Common** \> **All CIAP fixed assets**. Click **CIAP fixed asset** in the group on the **Action Pane**.

  


