---
title: Create cost categories
TOCTitle: Create cost categories
ms:assetid: 31e928ad-6b14-40f9-ac9d-fa8463458828
ms:mtpsurl: https://technet.microsoft.com/library/Aa570056(v=AX.60)
ms:contentKeyID: 36056349
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create cost categories 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up and link cost categories to the operations of any selected route, and therefore, define the hourly cost and processing times of the specified route.


> [!NOTE]
> <P>You must set up cost categories before you create production routes.</P>



1.  Click **Production control** \> **Setup** \> **Routes** \> **Cost categories**.

2.  Press CTRL+N to create a new line.

3.  Select the **Overview** tab, and in the **Category** field, enter a code of up to ten alphanumeric characters.

4.  In the **Cost price** field, enter the price per hour or per quantity for the cost category used to estimate the production cost.

5.  In the **Cost group** field, select a cost group to use in the current cost category.

6.  In the **Worker** field, select the worker associated with the cost category.
    
    The system suggests a worker automatically when entries are made in the consumption journal for the current cost category.

7.  Select the **Ledger - resources** tab, and if production is to be settled by applying **Item and category**, in the **WIP issue** field, select the issue account for operations resource consumption.

8.  In the **WIP account** field, select the receipt account for operations resource consumption if production is to be posted as **Item and category**.

9.  In the **Resource issues** field, select the ledger account to use for operations resource issues.

10. In the **Resource issues, offset account** field, select the offset account to use for posting operations resource issues when the production posted is **Item and category**.

## See also

[Create and update production routes](create-and-update-production-routes.md)

  


