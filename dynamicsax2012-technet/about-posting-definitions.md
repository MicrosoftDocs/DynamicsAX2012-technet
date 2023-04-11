---
title: About posting definitions
TOCTitle: About posting definitions
ms:assetid: a4f2e83d-2b87-40ec-b80a-522b953d424e
ms:mtpsurl: https://technet.microsoft.com/library/Hh242680(v=AX.60)
ms:contentKeyID: 36058863
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- posting definition
- posting definitions
- enable budget appropriations
- transaction posting defintions
- posting profiles
audience: Application User
ms.search.region: Global
---

# About posting definitions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Posting definitions are an alternative to posting profiles. You can use both posting definitions and posting profiles to create subledger journal lines for originating transactions that meet selected criteria. However, posting definitions and posting profiles are not interchangeable. You might have to use both to meet your organization’s needs.

You use posting definitions instead of posting profiles for the transaction types that you select in the **Transaction posting definitions** form. You must set up a posting profile or a posting definition for each posting type.

For more information, see [About posting profiles](about-posting-profiles.md).

## Posting definition considerations

You might want to use posting definitions in the following circumstances:

  - You have to generate multiple, balanced ledger entries based on attributes such as transaction types and accounts. Use posting profiles if you need only one offset ledger entry.

  - You have to support encumbrance accounting for purchase orders and pre-encumbrance accounting for purchase requisitions. Posting profiles cannot be used for encumbrance and pre-encumbrance accounting.

Posting definitions do not replace posting profiles. Even when you use posting definitions for offset accounts and encumbrance accounting, you still need posting profiles for the originating entry.

You should test posting definitions before you start to use them. When you select the **Use posting definitions** check box in the **General ledger parameters** form, all posting definitions become active.


> [!IMPORTANT]
> <P>To use posting definitions for budget register entries, you must also make the following selections:</P>
> <UL>
> <LI>
> <P>Select the <STRONG>Enable budget appropriation</STRONG> check box in the <STRONG>Ledger</STRONG> area of the <STRONG>General ledger parameters</STRONG> form.</P>
> <LI>
> <P>Select a budget journal in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>



## Prepare to create posting definitions

To prepare to create posting definitions, you might want to create diagrams or tables that illustrate each definition. For example, list the transaction data that a user might enter, and then list the entries that must be generated for the ledger accounts.

You can use posting definition versions with effective dates. For example, you can create a future version of a posting definition to post to a different ledger account in a new fiscal year.

You can link from one posting definition to another when you create posting definitions. This means that the criteria for the definition that you linked to are considered in addition to the criteria for the current posting definition. This saves time because you do not have to re-enter criteria on the **Entries** FastTab in the **Posting definitions** form for the current posting definition if you already entered those lines for another definition.

In the diagrams or tables, include any links that you might use. Make sure that the lines in any posting definitions that you are linking to are unique to avoid conflicts with the current posting definition.

The following restrictions apply when you create links in posting definitions:

  - Any posting definition can either link to another posting definition or be linked to from another posting definition, but not both. However, posting definitions that link to other posting definitions can link to multiple posting definitions.

  - You can set up links only among posting definitions that are in the same module.

  - You can assign a posting definition to any transaction type, but the transaction type must be in the same module as the posting definition. View the **Transaction posting definitions** form to see which module a transaction type is in.

In the **Posting definitions** form, you can assign priority numbers to entry lines to control the order in which the lines are evaluated. The lines with the lowest number are evaluated first, starting with 1, and then 2, and so on. When a match is found, the other match criteria are ignored. Also, only the criteria in the group that match the originating transaction create generated entries.

## Create posting definitions and assign them to transaction posting types

Use the **Posting definitions** form to specify the match criteria and to define the entries to generate when the match occurs. Use the **Transaction posting definitions** form to assign posting definitions to transaction types. For more information, see [Set up posting definitions](set-up-posting-definitions.md) and [Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md).

After you complete the setup in both the **Posting definitions** form and the **Transaction posting definitions** form, select the **Use posting definitions** check box in the **General ledger parameters** form to use posting definitions for your legal entity.


> [!IMPORTANT]
> <P>After you select this check box, all posting definitions are active immediately.</P>



For examples of posting definitions, see [Examples: Posting definitions](examples-posting-definitions.md).

## See also

[Posting definitions (form)](https://technet.microsoft.com/library/hh227607\(v=ax.60\))

[Transaction posting definitions (form)](https://technet.microsoft.com/library/hh242550\(v=ax.60\))

[Test Posting Definition Wizard (form)](https://technet.microsoft.com/library/hh227669\(v=ax.60\))

[About posting profiles](about-posting-profiles.md)

[Encumber purchase orders](encumber-purchase-orders.md)

  


