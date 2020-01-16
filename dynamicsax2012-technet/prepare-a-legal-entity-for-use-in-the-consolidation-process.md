---
title: Prepare a legal entity for use in the consolidation process
TOCTitle: Prepare a legal entity for use in the consolidation process
ms:assetid: 5ef6fbfa-9e22-4aa2-b4c3-b0e279d1035f
ms:mtpsurl: https://technet.microsoft.com/library/Aa549110(v=AX.60)
ms:contentKeyID: 39519155
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- consolidation
- legal entity
- consolidation process
audience: Application User
ms.search.region: Global
---

# Prepare a legal entity for use in the consolidation process 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In a consolidation, you gather transactions from several sets of legal entity accounts into a single set of legal entity accounts.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to combine the financial results for multiple legal entities in a consolidated format. Management Reporter lets you create consolidated financial reports across legal entities, use Microsoft Excel to import consolidation data from other sources, and translate amounts into any number of reporting currencies without having to run the consolidation process in Microsoft Dynamics AX.</P>
> <P>For more information about how to consolidate transactions by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=389548">Financial consolidations and currency translation</A>.</P>



You can print reports, such as financial statements, from the consolidated legal entity. However, you cannot use the consolidated legal entity for daily transactions.

You can consolidate data from legal entities that use different databases than the database for the consolidated legal entity. This consolidation process is referred to as an import consolidation. Alternatively, the legal entities can use the same database as the consolidated legal entity. This consolidation process is referred to as an online consolidation.

The consolidated legal entity collects the results and balances of the subsidiaries. To prepare a consolidated legal entity for a consolidation, you must follow these steps:

1.  Click **General ledger** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click **New** to create a new legal entity that will be the consolidated legal entity.

3.  Select the **Use for financial consolidation process** check box, and then enter information about the consolidated legal entity. Enter this information exactly as you want it to appear on financial statements for the consolidated legal entity.

4.  Close the form.

5.  In the lower-right corner of the Microsoft Dynamics AX workspace, click the **Current company** field to open the **Select company** form. Select the consolidated legal entity, and then click **OK**.

6.  Click **General ledger** \> **Setup** \> **Ledger**.

7.  Select the chart of accounts, the fiscal calendar, the accounting currency, an optional reporting currency, and the default exchange rate type for the consolidated legal entity. For more information, see [Ledger (form)](https://technet.microsoft.com/library/hh209331\(v=ax.60\)).

8.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency exchange rates**.

9.  Set up currency exchange rates in relevant periods for the currencies of the subsidiary legal entities. For more information, see [Currency exchange rates (form)](https://technet.microsoft.com/library/hh209477\(v=ax.60\)).

10. Close the form.

11. If the consolidated legal entity has subsidiaries that use foreign currencies, open the **Accounts for automatic transactions** form. (Click **General ledger** \> **Setup** \> **Posting** \> **Accounts for automatic transactions**.) In the **Posting type** field, select an appropriate account:
    
      - If the legal entity has foreign subsidiaries that are financially or operationally interdependent with the parent legal entity, select an appropriate account for the **Profit and loss account for consolidation differences** posting type.
    
      - If you are consolidating a subsidiary that is financially and operationally independent from the parent legal entity, or a legal entity that contains the results of several subsidiaries that are financially and operationally independent from the parent legal entity, and if you are using translation methods to consolidate the data, select an appropriate account for the **Balance account for consolidation differences** posting type.

12. In the **Main account** field, select the main accounts that will be used for foreign currency revaluation adjustments.

13. Close the form.

If you create the consolidated legal entity early in a period, you can revalue the foreign currency amounts as exchange rates change during the consolidation period.

The consolidated legal entity is now set up for the **Consolidate** periodic job. You can specify whether to perform either an online consolidation or an import consolidation:

Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Import from\]**.

–or–

Click **General ledger** \> **Periodic** \> **Consolidate** \> **Consolidate \[Online\]**.


> [!NOTE]
> <P>Before you can process the consolidation, prepare the subsidiary legal entities for consolidation. For more information, see <A href="set-up-a-subsidiary-legal-entity-for-consolidation.md">Set up a subsidiary legal entity for consolidation</A>.</P>


  


