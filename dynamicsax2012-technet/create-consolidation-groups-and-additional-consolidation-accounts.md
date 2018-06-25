---
title: Create consolidation groups and additional consolidation accounts
TOCTitle: Create consolidation groups and additional consolidation accounts
ms:assetid: 5bf62e29-c529-4c09-85ac-a54af389089b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ729754(v=AX.60)
ms:contentKeyID: 49564920
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accounts
- consolidation
- consolidation accounts
- consolidation groups
---

# Create consolidation groups and additional consolidation accounts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A consolidation account is the main account in the parent legal entity that is used for ledger consolidation. This legal entity is also known as the consolidated legal entity. When you use a consolidation account for consolidation, you can report financial information by using a statutory account number.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to combine the financial results for multiple legal entities in a consolidated format. Management Reporter lets you create consolidated financial reports across legal entities, use Microsoft Excel to import consolidation data from other sources, and translate amounts into any number of reporting currencies without having to run the consolidation process in Microsoft Dynamics AX.</P>
> <P>For more information about how to consolidate transactions by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=389548">Financial consolidations and currency translation</A>.</P>



If you use additional consolidation accounts, you must create a consolidation account group and additional consolidation accounts before you start the consolidation process.

## Create a consolidation account group

Some organizations have legal entities in multiple countries/regions. Some of those legal entities might be required to report information to local governments by using a government-mandated chart of accounts. You can use consolidation accounts and consolidation account groups for this reporting. For example, if your local government requires that your organization submit a statutory chart of accounts for reporting purposes, you can create a consolidation account group to represent this statutory chart of accounts.

Use the **Consolidation account groups** form to create groups of consolidation accounts that can be used to represent additional charts of accounts.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Consolidation account groups**.

2.  Click **New**.

3.  Enter a unique identifier and a name for the consolidation account group.

## Create additional consolidation accounts

You can enter one default consolidation account for each main account in the **Main accounts - chart of accounts: %1** form. To enter additional consolidation accounts, use the **Additional consolidation accounts** form to create and maintain consolidation accounts for the combination of the consolidation account group and the main account that you specify. Each consolidation account must be unique for each combination of a consolidation account group and a main account.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Additional consolidation accounts**.

2.  Click **New**.

3.  Select the chart of accounts that contains the main account for which to create additional consolidation accounts.

4.  Select the main account to which to assign a consolidation account group and a consolidation account.

5.  Select a consolidation account group by which to classify the consolidation account. For example, to group all consolidation accounts for the French statutory chart of accounts, you can create a consolidation group that is named **French chart of accounts**.

6.  Enter a consolidation account number. This number must be unique for each combination of a main account and a consolidation account group.

7.  Enter the name of the consolidation account.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

