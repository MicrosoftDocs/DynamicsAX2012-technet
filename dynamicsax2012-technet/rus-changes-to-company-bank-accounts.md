---
title: (RUS) Changes to company bank accounts
TOCTitle: (RUS) Changes to company bank accounts
ms:assetid: 12d801f0-f8af-4b77-92fd-2a88b155edc5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711404(v=AX.60)
ms:contentKeyID: 49387222
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- company
- bank accounts
- (RUS)
- Russia
---

# (RUS) Changes to company bank accounts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The status of the bank account for an organization determines the account reconciliation, transaction posting, and statement generation processes. The status of a bank account can be inactive either for all transactions or only for new transactions that are created after the account is inactivated. If the status of the bank account is inactive for all transactions, you cannot post any outgoing or incoming payments and payment receipt transactions. You cannot generate incoming or outgoing transaction statements for inactive bank accounts. If the status is inactive for new transactions, you cannot post incoming payments, but you can post outgoing payments for transactions that were posted when the account was active.

You cannot change the bank account status to inactive if the account has any vendor transactions that are open. You also cannot use the **Transit account** function to change the date of a posted transaction when you reconcile a bank account that is inactive.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

