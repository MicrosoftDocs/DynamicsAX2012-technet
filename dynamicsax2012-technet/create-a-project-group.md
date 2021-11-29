---
title: Create a project group
TOCTitle: Create a project group
ms:assetid: 9ffaabe6-3a16-4f47-91c3-e0351b642e7c
ms:mtpsurl: https://technet.microsoft.com/library/Hh370698(v=AX.60)
ms:contentKeyID: 36811422
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project group
audience: Application User
ms.search.region: Global
---

# Create a project group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Every project must be associated with a project group. The project must be of the same type as the project group that it is associated with. The primary purpose for assigning projects to groups is to control how posting to general ledger accounts is set up. For Fixed-price and Investment projects, the project groups also specify a cost template, which controls estimate costs, and a period code, which determines how frequently estimates are calculated for projects that are associated with the project group.

You can set up project groups for all types of projects in Microsoft Dynamics AX.

You can change the project group for a project before or after project transactions have been posted, subject to certain limitations. For more information, see [About changing the project group](about-changing-the-project-group.md).

1.  Click **Project management and accounting** \> **Setup** \> **Posting** \> **Project groups**.

2.  Click **New**.

3.  In the **Project group** field, enter an identifier for the group.

4.  In the **Name** field, enter a name to identify the group.

5.  On the **General** FastTab, in the **Project type** field, select the type of projects to include in the group.

6.  Optional: Select the default line property for the group, and specify whether the ledger and the line property are posted according to the project settings or the category settings.

7.  On the **Ledger** FastTab, specify the type of ledger account that project costs and on-account invoices are posted to when the transactions are posted.
    

    > [!IMPORTANT]
    > <P>For Fixed-price projects, the <STRONG>On-account invoicing</STRONG> field is available only after you select a revenue recognition accounting rule on the <STRONG>Estimate</STRONG> FastTab.</P>



8.  On the **Estimate** FastTab, set up options for revenue recognition and estimate categories.
    
    If the total estimated costs exceed either the contract value for a Fixed-price project or the maximum capitalization limit for an Investment project, and you want losses to be recognized immediately, select the **Foreseeable losses** check box.

9.  Optional: On the **Cost accounts** and **Revenue accounts** FastTabs, define the default accounts for projects that are associated with the project group.

## See also

[About project groups](about-project-groups.md)

[About changing the project group](about-changing-the-project-group.md)

[Change the project group](change-the-project-group.md)

  


