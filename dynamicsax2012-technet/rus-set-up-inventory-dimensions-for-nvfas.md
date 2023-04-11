---
title: (RUS) Set up inventory dimensions for NVFAs
TOCTitle: (RUS) Set up inventory dimensions for NVFAs
ms:assetid: 499128df-e418-4afb-809e-a539ffc85c00
ms:mtpsurl: https://technet.microsoft.com/library/JJ911373(v=AX.60)
ms:contentKeyID: 52075377
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Russia
- NVFA
- inventory dimension
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up inventory dimensions for NVFAs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up inventory dimensions for not valuable fixed assets (NVFAs), working clothes, and special rigging items.

1.  Click **Product information management** \> **Setup** \> **Dimension groups** \> **Tracking dimension groups**.

2.  Create a new dimension group.

3.  Select the **Active** check box for the **Batch number** dimension to enable batch accounting for NVFAs, working clothes, and special rigging items. Items that have different prices are accounted for in different batches.

4.  Select the **Primary stocking** and **Financial inventory** check boxes for the **Batch number** dimension.

5.  Select the **Active** check box for the **Serial number** dimension. This dimension is used when the asset is put into operation.

6.  Select the **Blank receipt allowed** and **Blank issue allowed** check boxes for the **Serial number** dimension. When these check boxes are selected, you can perform inventory operations without specifying a serial number.

## See also

[Tracking dimension groups (form)](https://technet.microsoft.com/library/hh209465\(v=ax.60\))

[(RUS) Set up item details for NVFAs](rus-set-up-item-details-for-nvfas.md)

  


