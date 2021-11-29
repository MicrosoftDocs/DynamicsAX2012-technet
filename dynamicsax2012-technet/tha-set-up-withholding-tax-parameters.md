---
title: (THA) Set up withholding tax parameters
TOCTitle: (THA) Set up withholding tax parameters
ms:assetid: 6826cff0-fd92-4d12-b9a6-364eeef77beb
ms:mtpsurl: https://technet.microsoft.com/library/Hh242602(v=AX.60)
ms:contentKeyID: 36057952
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Thailand
- withholding tax
audience: Application User
ms.search.region: Thailand
---

# (THA) Set up withholding tax parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

All businesses in Thailand are required to calculate withholding taxes for services that they provide and to record withholding taxes deducted for services received. Withholding tax reports must be sent to the government tax authorities on a regular basis. In accordance with tax regulations, you must set up item tax groups and attach them to service items to calculate withholding taxes. You must set up ledger posting groups to define the ledger accounts to post the withholding tax transactions, set up withholding tax thresholds, and set up currency codes and rates.

## Configuration setup

1.  Click **System administration** \> **Setup** \> **Licensing** \> **License configuration**.

2.  Expand the **General ledger** node and select the **Withholding tax** check box.

3.  Click **OK** to save your changes.

## Parameter setup

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Withholding tax** link, in the **Minimum invoice amount** field, enter the minimum threshold for withholding tax reporting. Withholding tax is calculated only when the invoice is equal to or greater than the specified threshold.

3.  Close the form to save your changes.

## See also

[General ledger parameters (form)](https://technet.microsoft.com/library/aa557286\(v=ax.60\))

  


