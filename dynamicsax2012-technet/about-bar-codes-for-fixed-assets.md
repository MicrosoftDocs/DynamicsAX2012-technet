---
title: About bar codes for fixed assets
TOCTitle: About bar codes for fixed assets
ms:assetid: 729076d0-4e02-4a82-8607-4fb5927f0877
ms:mtpsurl: https://technet.microsoft.com/library/Aa549986(v=AX.60)
ms:contentKeyID: 36058123
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About bar codes for fixed assets 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If the **Bar code equals fixed asset number** check box is selected in the **Fixed assets parameters** form, a bar code is assigned when you create a fixed asset.

If the check box is not selected and the bar code is set up in the fixed assets group, you must generate a periodic job to assign bar codes. You can do this if you want to wait to decide to use bar codes, and subsequently, the bar codes can be allocated later.

You can assign bar codes even if the **Autonumber fixed assets** check box is not selected in the **Fixed assets parameters** form. In this case, fixed asset numbers are allocated manually, and the periodic job, **Assign fixed asset number to bar code**, assigns the fixed asset number and the bar code number, also. The only prerequisite is that the **Bar code equals fixed asset number** check box is selected in the **Fixed assets parameters** form.

You can print a **Fixed asset bar codes** report. (Click **Fixed assets** \> **Reports** \> **Base data** \> **Fixed asset bar codes**.)

## See also

[Assign fixed asset numbers to bar codes](assign-fixed-asset-numbers-to-bar-codes.md)

  


