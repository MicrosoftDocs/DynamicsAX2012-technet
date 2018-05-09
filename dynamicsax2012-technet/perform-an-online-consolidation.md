---
title: Perform an online consolidation
TOCTitle: Perform an online consolidation
ms:assetid: a0deda69-d53e-4eb7-9b0b-01ae925c2621
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571755(v=AX.60)
ms:contentKeyID: 37832519
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- online
- consolidation
- online consolidation
---

# Perform an online consolidation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An online consolidation is a consolidation where the subsidiary legal entities are in the same database as the consolidated legal entity.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to combine the financial results for multiple legal entities in a consolidated format. Management Reporter lets you create consolidated financial reports across legal entities, use Microsoft Excel to import consolidation data from other sources, and translate amounts into any number of reporting currencies without having to run the consolidation process in Microsoft Dynamics AX.</P>
> <P>For more information about how to consolidate transactions by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=389548">Financial consolidations and currency translation</A>.</P>



Follow these steps to do an online consolidation:

1.  Set up the consolidated legal entity and the accounts of the subsidiaries, which are the legal entities to be consolidated. For information, see [Prepare a legal entity for use in the consolidation process](prepare-a-legal-entity-for-use-in-the-consolidation-process.md) and [Set up a subsidiary legal entity for consolidation](set-up-a-subsidiary-legal-entity-for-consolidation.md).

2.  Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Online\]**.

3.  In the **Consolidate** \[**Online**\] form, prepare the transfer of subsidiary data to the consolidated legal entity.

4.  On the **Criteria** tab, specify the details of the consolidation. If the same criteria apply, you can transfer data from several subsidiaries to the consolidated legal entity by using a single operation.

5.  Click the **Financial dimensions** tab, and specify the financial dimension information to transfer from the transactions in the subsidiary accounts to the transactions in the consolidated legal entity.

6.  Click the **Legal entities** tab, and create a line for each subsidiary legal entity whose data is being imported into the consolidated legal entity. Specify the following information for each subsidiary:
    
      - If the consolidated legal entity owns part of a subsidiary, specify the share of the subsidiary accounts to import.
    
      - If you are consolidating subsidiaries that use foreign currencies, in the **Account type of conversion differences** field, specify whether consolidation exchange differences are posted to a balance account or to a profit and loss account in the consolidated legal entity.

7.  Click **Batch** to set up the consolidation to run as a batch job at the time that you prefer, or click **OK** to run the consolidation immediately.
    
    The transactions and balances that were specified for consolidation in the subsidiaries are added to the appropriate accounts in the consolidated legal entity.


> [!NOTE]
> <P>If there are previous consolidation transactions for the same legal entity, date, and account range, the transactions will be removed and consolidated again.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

