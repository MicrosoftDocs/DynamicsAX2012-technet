---
title: Set up General ledger year-end processes (Public sector)
TOCTitle: Set up General ledger year-end processes (Public sector)
ms:assetid: 3ddecfa3-ea60-4bbe-a323-95ac0954d92a
ms:mtpsurl: https://technet.microsoft.com/library/Hh208524(v=AX.60)
ms:contentKeyID: 36056272
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- setup
- how to
- howto
- how-to
- public sector
- end of year
- end of year closing
- funds
- general ledger closing
- GL
- non-funds
- set up
- year-end close
- year end close
- year-end closing
audience: Application User
ms.search.region: Denmark, France
---

# Set up General ledger year-end processes (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

At the end of a fiscal year, you must generate closing transactions and prepare your accounts for the next fiscal year. You can select accounts by fund for year-end closing and also close to different accounts. For example, you can close nominal accounts associated with governmental funds to fund balance, and close nominal accounts associated with proprietary funds to retained earnings. You can also set up year-end closing for all funds and non-funds. Non-funds do not have a fund dimension in the account structure. For more information about year-end closing, see [Fiscal year closing checklist](fiscal-year-closing-checklist.md).


> [!NOTE]
> <P>This process is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



You can set up multiple closing periods to segregate different types of closing entries, such as general year-end closing and audit adjustments.

If you are in the public sector and are using general budget reservations, see also [Finalize a general budget reservation (Public sector)](finalize-a-general-budget-reservation-public-sector.md) and [Carry forward general budget reservation information to a new fiscal year (Public sector)](carry-forward-general-budget-reservation-information-to-a-new-fiscal-year-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



To set up year-end processes, complete the following tasks:

1.  Select a closing type for the closing account, such as nominal or real. For more information, see [Main accounts - chart of accounts (form)](https://technet.microsoft.com/library/hh209695\(v=ax.60\)).

2.  [Set up posting definitions](set-up-posting-definitions.md): Define which originating and generated accounts will be updated at closing.
    

    > [!IMPORTANT]
    > <P>In the <STRONG>Generated debit/credit</STRONG> field, select <STRONG>Balancing</STRONG> for generated entries. The first generated account that you enter will automatically be the offset (balancing) account, even if you select <STRONG>Same</STRONG>.</P>



3.  [Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md): Assign definitions by fund class for opening and closing transactions. You can also assign definitions to all funds and non-funds.

4.  [Transfer opening balances to a new fiscal year](transfer-opening-balances-to-a-new-fiscal-year.md):
    
    1.  Select the calendar and fiscal year to process.
    
    2.  Select the periods through which balances will be used to create closing and opening entries.
    
    3.  Select the funds to process. You can process a single fund, range of funds, or all funds.
    
    4.  Optional: Preview transactions before posting to the General ledger.

## See also

[Posting definitions (form)](https://technet.microsoft.com/library/hh227607\(v=ax.60\))

[Transaction posting definitions (form)](https://technet.microsoft.com/library/hh242550\(v=ax.60\))

[Opening transactions (form)](https://technet.microsoft.com/library/aa572506\(v=ax.60\))

[Preview year-end General ledger transactions (form) (Public sector)](https://technet.microsoft.com/library/hh208564\(v=ax.60\))

  


