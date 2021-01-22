---
title: Create and use scoring criteria and methods
TOCTitle: Create and use scoring criteria and methods
ms:assetid: cbf3cf00-8521-420a-9448-a3586566538c
ms:mtpsurl: https://technet.microsoft.com/library/Dn621062(v=AX.60)
ms:contentKeyID: 62200160
author: Khairunj
ms.author: daxcpft
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- rank
- method
- procurement
- methods
- score
- PurchRFQCaseTableListPage
- PurchRFQSolicitationType
- PurchRFQScoringMethod
- Forms.PurchRFQScoringMethod
- scores
- scoring method
- comparison
- criteria
- criterion
- scoring criteria
audience: Application User
ms.search.region: Global
---

# Create and use scoring criteria and methods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This feature is available only if **eProcurement** in Microsoft Dynamics AX 2012 R3 is installed.

When you evaluate bids, you can score the bids to help rank them. Typically, a purchasing manager creates one or more scoring methods that are associated with requests for quotation (RFQs). Additionally, the purchasing manager creates a set of scoring criteria for each method. Each criterion can be scored in a given range. A default scoring method can be associated with each RFQ solicitation type, or a purchasing agent can assign a scoring method when the RFQ is created.

## Create a scoring method and criteria

Use this procedure to create a method for scoring bids.

1.  Click **Procurement and sourcing** \> **Setup** \> **Request for quotation** \> **Scoring method**.

2.  In the **Scoring method** form, click **New**.

3.  Enter a name and description for the new scoring method.

4.  In the **Scoring criteria** area, click **New**.

5.  Enter a name, description, and range for the new scoring criterion. For example, a range can be a point system, such as 1 to 5, –10 to +10, or 0 to 100.

6.  To add more criteria, repeat steps 4 and 5. When you have added all the criteria that you require, click **Close**.

## Set a default scoring method

Typically, a default scoring method is associated with an RFQ’s solicitation type. Therefore, when you create an RFQ of a particular solicitation type, the RFQ automatically uses that scoring method. For information about how to create a new solicitation type and assign a default scoring method, see [Create and use a solicitation type](create-and-use-a-solicitation-type.md).

1.  Click **Procurement and sourcing** \> **Setup** \> **Request for quotation** \> **Solicitation type**.

2.  In the **Solicitation type** form, click an entry in the **Name** column.

3.  In the **Scoring method** list, select a method.
    
    When you create an RFQ with this type, the selected scoring method will be associated with it.

4.  Click **Close**.
    

    > [!NOTE]
    > <P>If the existing scoring methods or criteria aren’t sufficient, use the first procedure in this topic to create a new method or new criteria.</P>



## Add scoring criteria to an RFQ

Use this procedure if you want to add or change scoring criteria for a specific RFQ. You can only add or change scoring criteria if no scoring has been done for the RFQ.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Open the RFQ that you want to work with.

3.  On the **Request for quotation details** page, on the **Action pane**, click **Scoring criteria**.

4.  Click **New**.

5.  Enter a name, description, and range, and then click outside out of the grid.
    
    The new scoring criteria record is saved.


> [!NOTE]
> <P>You can also add a new scoring method that extends or replaces the existing list of criteria.</P>



For information about how to score bids that you have received, see [Compare bids and award a contract](compare-bids-and-award-a-contract.md).

  


