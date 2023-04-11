---
title: About journal setup
TOCTitle: About journal setup
ms:assetid: 0152eb50-2b7e-4b24-99d6-bdff22c870ef
ms:mtpsurl: https://technet.microsoft.com/library/Hh696873(v=AX.60)
ms:contentKeyID: 42517315
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About journal setup 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use journals to enter transactions for project beginning balances and to assign the cost of hours, expenses, items, and fees to projects.

Before you create project journals, you can set up default values for journal names. The default names are automatically added to new project journals. The journal name contains setup information about journals. You can set up any number of journal names for projects, and any number of journals can use the same journal name. The journal name contains information such as the voucher series and the method for changing the voucher number.

Set up project journal names and other default information for journals in the **Project management and accounting parameters** form. Set up journal names for other project costs in **General ledger**, and for item purchases in **Inventory management**. For more information, see [Set up project journal names](set-up-project-journal-options.md).

Optionally, you can set up requirements that journal lines cannot be processed until related tasks are completed and approved. For example, you can use a journal approval procedure to require approval of hours that are submitted on timesheets before the related hour journal is posted. If you select an approval procedure for a journal name, this approval procedure will be required for all journals that have this journal name. For more information, see [About journal approval procedures](about-journal-approval-procedures.md).

You can create journal descriptions and add them to new hour and fee journals. In a journal line, you select the identifier for a journal description, and the related block of text is inserted in the **Description** field in a journal. For more information, see [Create journal descriptions](create-journal-descriptions.md).

## See also

[Create a project beginning balance](create-a-project-beginning-balance.md)

  


