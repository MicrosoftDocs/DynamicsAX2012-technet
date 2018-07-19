---
title: View and delete consolidation transactions
TOCTitle: View and delete consolidation transactions
ms:assetid: 2c3f82ad-040f-4cd8-a896-af8bdbe25b0d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496867(v=AX.60)
ms:contentKeyID: 36056257
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- transactions
- consolidation
- consolidation transactions
audience: Application User
ms.search.region: Global
---

# View and delete consolidation transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Consolidating the accounts of various subsidiaries can be time-consuming, and sometimes the records that were created for one subsidiary must be revised. Instead of repeating the consolidations of all the subsidiaries, you can delete the transactions that were created from a particular subsidiary and then run that consolidation again.

1.  Click **General ledger** \> **Inquiries** \> **Consolidations**.

2.  On the **Overview** tab, view the list of consolidation periodic jobs by subsidiary that contribute to the consolidated legal entity.

3.  To view the ledger transactions or budget register entries from a particular subsidiary in a selected consolidation periodic job, click **Transactions**, and then click **Current** (ledger) or **Budget**.

4.  To delete the transactions in the selected consolidation, click **Remove transactions** in the **Consolidations** form. This removes the previous consolidation data from the database and removes subsidiary data that must be added again.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to combine the financial results for multiple legal entities in a consolidated format. Management Reporter lets you create consolidated financial reports across legal entities, use Microsoft Excel to import consolidation data from other sources, and translate amounts into any number of reporting currencies without having to run the consolidation process in Microsoft Dynamics AX.</P>
> <P>For more information about how to consolidate transactions by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=389548">Financial consolidations and currency translation</A>.</P>


  


