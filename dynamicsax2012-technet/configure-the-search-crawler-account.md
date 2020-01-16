---
title: Configure the Search Crawler account
TOCTitle: Configure the Search Crawler account
ms:assetid: ae8848a8-308d-4158-bb29-356ed00dd9e2
ms:mtpsurl: https://technet.microsoft.com/library/Gg731895(v=AX.60)
ms:contentKeyID: 35132811
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure the Search Crawler account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to configure the Enterprise Search crawler account so that the Microsoft SharePoint indexing service can crawl Microsoft Dynamics AX data for Enterprise Search. Before you can configure the account, you must create a domain account for the search crawler. For more information, see [Create service accounts](create-service-accounts.md).

1.  Add the domain account as a user in Microsoft Dynamics AX. For more information, see [Create new users in Microsoft Dynamics AX](create-new-users-in-microsoft-dynamics-ax.md).

2.  Assign the user to the Search crawler role in Microsoft Dynamics AX. For more information, see [Assign users to security roles](assign-users-to-security-roles.md).

3.  Repeat this procedure for each data partition. If you do not add the Search crawler account to a data partition, users will not see search results for that partition. For more information about data partitions, see [Data partitioning architecture](data-partitioning-architecture.md).

## See also

[Checklist: Deploy Microsoft Dynamics AX Enterprise Search](checklist-deploy-microsoft-dynamics-ax-enterprise-search.md)

[Install Microsoft Dynamics AX Enterprise Search](install-microsoft-dynamics-ax-enterprise-search.md)

  


