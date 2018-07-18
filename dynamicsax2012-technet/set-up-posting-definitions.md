---
title: Set up posting definitions
TOCTitle: Set up posting definitions
ms:assetid: d0a60e04-9d31-4284-bfc9-f890b41c1708
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242920(v=AX.60)
ms:contentKeyID: 36059490
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- create posting definitions
- post definition prerequisites
- posting defintions
- set up posting definitions
audience: Application User
ms.search.region: Global
---

# Set up posting definitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Posting definitions are used to define ledger line entries that are generated when a match exists between an originating transaction and the match criteria that you specify.

If you’re in the public sector and use general budget reservations, see also [Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



After you create posting definitions, you need to assign them to transaction types by using the **Transaction posting definitions** form. Transaction posting definitions specify transaction attributes, such as item codes for purchase orders or account codes for vendor invoices. They also identify which posting definitions to use with a specific transaction type. For more information, see [Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md).

## Prerequisites

  - To use posting definitions for budget register entries, make the following selections:
    
      - In the **General ledger parameters** form, on the **Accounting rules** FastTab, select the **Enable budget appropriation** check box.
    
      - In the **Budget parameters** form, select a budget journal.

  - If the **Public Sector** configuration key is selected, do the following to use posting definitions for year-end closing and opening in the general ledger:
    
      - In the **General ledger parameters** form, on the **Fiscal year close** FastTab, select the **Create closing transactions during transfer** check box.
    
      - In the **Main accounts - chart of accounts: %1** form, create a closing account.

## Create posting definitions

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Posting definitions**.

2.  Click **New** to create a posting definition.

3.  Enter a name and description for the posting definition. You can enter additional details on the **Memo** FastTab.

4.  Select the module that the posting definition applies to.

5.  Specify the effective and expiration dates.
    

    > [!NOTE]
    > <P>To modify an existing posting definition, click <STRONG>New version</STRONG> and enter new effective and expiration dates. You can modify or add match criteria and generated entries.</P>



6.  On the **Entries** FastTab, under **Match criteria**, click **Add**, and then select an account structure. In the **Match account number** field, enter the account segments that must be in the originating transaction.
    

    > [!TIP]
    > <P>To match any value, leave the <STRONG>Match account number</STRONG> field blank. For example, 11005-BLANK-BLANK will match any account that starts with 11005.</P>



7.  Optional: If you have multiple lines of match criteria, in the **Priority** field, enter a number to indicate the order in which the match criteria should be processed. Lines that have a priority of 1 are processed first.

8.  Under **Generated entries**, click **Add**, and select an account structure. In the **Generated account number** field, enter the account segments for which a ledger line will be generated when there is a match.
    

    > [!TIP]
    > <P>To inherit any value, leave the <STRONG>Generated account number</STRONG> field blank.</P>



9.  In the **Generated debit/credit** field, select **Same** if the generated entry is the same as the originating one. Select **Balancing** to balance the generated and originating entries.
    

    > [!IMPORTANT]
    > <P>To generate closing entries for the public sector, select <STRONG>Balancing</STRONG>. The first account that you enter will automatically be the offset (balancing) account, even if you select <STRONG>Same</STRONG>.</P>



10. Optional: To link to an existing posting definition, click the **Linked definitions** FastTab and then click **Add**. Linked posting definitions must be associated with the same module.
    
    The **Linked definitions** FastTab is displayed only if the current posting definition is not linked to another posting definition. If it is already linked to another definition, the **Used as link in** FastTab is displayed.

11. Optional: To test the posting definition, click **Test**. A test lets you enter sample transaction data and then view the system-generated ledger lines that will result when the posting definition is used.

## See also

[About posting definitions](about-posting-definitions.md)

[Examples: Posting definitions](examples-posting-definitions.md)

[Posting definitions (form)](https://technet.microsoft.com/en-us/library/hh227607\(v=ax.60\))

[Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md)

[Transaction posting definitions (form)](https://technet.microsoft.com/en-us/library/hh242550\(v=ax.60\))

[Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md)

  


