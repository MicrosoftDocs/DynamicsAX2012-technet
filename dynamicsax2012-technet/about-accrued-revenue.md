---
title: About accrued revenue
TOCTitle: About accrued revenue
ms:assetid: cddc3a3d-e168-4377-8659-9a845a97afc6
ms:mtpsurl: https://technet.microsoft.com/library/Aa572687(v=AX.60)
ms:contentKeyID: 42117779
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accrued revenue
- WIP sales value
audience: Application User
ms.search.region: Global
---

# About accrued revenue 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

For Fixed-price projects and Time and material projects, revenue can be accrued only if the project is assigned to a project group for which accruals are enabled. Furthermore, you must enable accruals in the line property setting for the transaction. To enable accruals, select the **Accrue revenue** check box in the **Line properties** form for the specified line property.

For Time and material projects, this makes sure that project revenue and related costs are recognized in the same accounting period. For accrued revenue that is related to both expenses and hours, the revenue amount is posted as a debit to the **WIP - sales value** account on the balance sheet and posted as credit to the **Accrued revenue - sales value** account on the profit and loss statement.

During the course of a Fixed-price project, you can accrue revenue as project costs accumulate by using the Microsoft Dynamics AX estimate system. When you complete a Fixed-price project, the accrued revenue amounts are reversed and the actual project revenue is recognized.

## See also

[About line properties](about-line-properties.md)

[About project groups](about-project-groups.md)

[About estimates](about-estimates.md)

  


