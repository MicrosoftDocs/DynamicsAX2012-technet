---
title: About intercompany master scheduling
TOCTitle: About intercompany master scheduling
ms:assetid: 908786da-80d5-4abc-b367-53ce45f82e00
ms:mtpsurl: https://technet.microsoft.com/library/Aa498368(v=AX.60)
ms:contentKeyID: 36058536
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- intercompany
- master scheduling
audience: Application User
ms.search.region: Global
---

# About intercompany master scheduling 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Intercompany master scheduling is the means by which you calculate requirements and generate planned intercompany orders across several internal companies. Intercompany master scheduling is carried out over the number of iterations that you specify. To enable Microsoft Dynamics AX to carry out intercompany master scheduling, you must set up master scheduling in each of your intercompany companies. This entails a number of iterations in which Microsoft Dynamics AX automatically creates an intercompany purchase order; this, in turn, leads to the automatic creation of an intercompany sales order, which again leads to new demands.

You set up the intercompany master plan and the intercompany scheduling order in the **Master planning** parameters in each of the intercompany companies.

In order to propagate the demand throughout the intercompany chain, you must set parameters to ensure that planned purchase orders are automatically firmed; that is, orders cannot be changed in terms of time or quantity. Set up the **Firming time fence** on the Coverage group, or the **Firming time fence** in the Master plan. If no **Firming time fence** is set up, no intercompany purchase orders are created automatically. Only the first execution of the master scheduling results in planned orders; however, because the intercompany purchase order is not actually created, no intercompany sales order is created, and, therefore, no additional intercompany purchase orders are created, and so on.

When you start the intercompany master scheduling, Microsoft Dynamics AX performs one master scheduling in each intercompany company; then, it performs a second master scheduling in each intercompany company, and so on, until the specified number of iterations is reached. A maximum of 30 iterations is possible; however, the more iterations that you choose, the longer the scheduling takes.

Because the master scheduling in the companies is controlled by the intercompany scheduling sequence, that is, the order in which the program prioritizes the master schedules between each intercompany company, you can start the intercompany master scheduling from any of the intercompany companies. Because the intercompany scheduling sequence determines the order in which the master scheduling is performed in the companies, it is not important where the intercompany master scheduling is started. In each iteration, the current company executes last.


> [!NOTE]
> <P>The best practice is to allow intercompany master scheduling to be initiated from one Microsoft Dynamics AX company.</P>



In the **Intercompany master scheduling** form, you can start a sequence of master scheduling, which executes a master scheduling the first time with the principle for updating the requirement calculation that you have selected for the first iteration for all the intercompany companies. Subsequent iterations use the secondary principle that you select for the next iteration, and this principle is applied until the number of iterations that you have specified is reached.

  


