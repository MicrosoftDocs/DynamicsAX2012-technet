---
title: Set up a ledger
TOCTitle: Set up a ledger
ms:assetid: 89a050d9-71d8-4dfe-8ae5-b2f6d55a8cf8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh416704(v=AX.60)
ms:contentKeyID: 36931875
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ledger
- ledger setup
- set up a ledger
---

# Set up a ledger 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you create a legal entity, you must create a ledger for that legal entity. You can have only one ledger for each legal entity. You can use information that has already been set up for other legal entities, such as charts of accounts, account structures, fiscal calendars, and currencies, or you can set up new information.

Although you can use financial dimensions to represent legal entities without creating the legal entities in Microsoft Dynamics AX, financial dimensions aren’t designed to address the operational or business needs of legal entities. The interunit accounting functionality in Microsoft Dynamics AX is designed to address only the accounting entries that are created by each transaction.

Before you set up financial dimensions as legal entities, evaluate your business processes in the following areas to determine if this setup will work for your organization:

  - Inventory

  - Sales and purchases between financial dimensions and legal entities

  - Sales tax calculation and reporting

  - Operational reporting

Some examples of the limitations include the following:

  - You can use sales tax functionality only with legal entities, not with financial dimensions.

  - Some reports don't include financial dimensions, so you can't always report by financial dimension unless those reports are modified.

In the **Ledger** form, you can also select a balancing financial dimension, which requires that all new accounting entries must be balanced for each value for that financial dimension. For more information, see [Example: Balanced accounting entry for interunit accounting](example-balanced-accounting-entry-for-interunit-accounting.md).


> [!NOTE]
> <P>After you post journal entries, you cannot change the chart of accounts or currencies in the <STRONG>Ledger</STRONG> form. Use the <STRONG>Ledger accounting currency conversion</STRONG> and <STRONG>Ledger reporting currency conversion</STRONG> forms to change the currencies.</P>



1.  Click **General ledger** \> **Setup** \> **Ledger**.

2.  Select a chart of accounts.

3.  To add an account structure to the ledger, click **Add**, and then double-click an account structure. You can also click **Configure account structures** to create account structures.
    
    You must select at least one account structure before you can record a source document or journal entry for the legal entity that the ledger is created for.

4.  Optional: Select the financial dimension that must be balanced in all accounting entries. If you select a balancing financial dimension, you must select a financial dimension that is included in all account structures that are assigned to the ledger.
    

    > [!WARNING]
    > <P>If you select a value in this field, only accounting entries are balanced. Your organization’s operational processes are not considered.</P>



5.  Select a fiscal calendar for the legal entity.

6.  Select an accounting currency and a reporting currency for the legal entity.

7.  Select default exchange rate and budget exchange rate types.

8.  For each posting type, select a main account. When a currency is revalued, the differences are posted to this account, depending on the posting type.

## See also

[Create or modify a legal entity](create-or-modify-a-legal-entity.md)

[Set up a chart of accounts](set-up-a-chart-of-accounts.md)

[Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md)

[Create a currency code](create-a-currency-code.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

