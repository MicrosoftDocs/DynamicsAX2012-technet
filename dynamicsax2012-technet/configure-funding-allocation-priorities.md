---
title: Configure funding allocation priorities
TOCTitle: Configure funding allocation priorities
ms:assetid: 0e80d919-6f09-4ad9-a294-84a1f205169b
ms:mtpsurl: https://technet.microsoft.com/library/Hh242133(v=AX.60)
ms:contentKeyID: 36056011
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advanced funding
- funding allocation order
- funding allocation priority
- lock allocation settings
audience: Application User
ms.search.region: Global
---

# Configure funding allocation priorities 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When multiple funding sources bear the costs for projects that are associated with a single project contract, it is necessary to define details such as which source is responsible for which kinds of transactions, what percentage of the overall costs a particular funder is responsible for, and which aspects of a project are funded first from the available funds.

In the **Project contracts** form, you create funding rules, which specify the order, or priority, in which funding rules are applied for a specific project contract. In the **Project parameters** form, you specify whether those priority settings for an individual project contract take precedence over the funding allocation settings that you set up for an entire organization.

For information about setting up funding rules for a project contract, including priority settings, see [Set up funding rules for a project contract](set-up-funding-rules-for-a-project-contract.md).

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the left pane, click **Invoice**.

3.  Under **Funding allocation order**, use the **Up** and **Down** buttons to set the order in which to allocate funding for the project dimensions in the list.

4.  If you want the funding rules for a project contract to take precedence over the organization-wide funding allocation settings, move **Priority** to the top of the list.
    
    –or–
    
    If you want the organization-wide funding allocation settings to take precedence over the funding rules for a project contract, move **Priority** to the bottom of the list.

5.  Optional: When you finish configuring the funding allocation priority settings, select the **Lock allocation settings** check box to prevent unintended changes to the settings.

## See also

[Set up project contract funding](set-up-project-contract-funding.md)

[About project contract funding](about-project-contract-funding.md)

[Assign funding sources to a project contract](assign-funding-sources-to-a-project-contract.md)

[Set up funding limits for funding sources in a project contract](set-up-funding-limits-for-funding-sources-in-a-project-contract.md)

[Set up funding rules for a project contract](set-up-funding-rules-for-a-project-contract.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

  


