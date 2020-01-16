---
title: (FRA) Process purchase order encumbrances and commitments at year end (Public sector)
TOCTitle: (FRA) Process purchase order encumbrances and commitments at year end (Public sector)
ms:assetid: 3fdb7b79-2297-47e1-996a-4da7479a979d
ms:mtpsurl: https://technet.microsoft.com/library/Hh208527(v=AX.60)
ms:contentKeyID: 36056276
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- commitments
- public sector
- commitment
- France
- French
- year end
- year-end
- encumbrance
- encumbrances
- purchase order encumbrances
- end of the year
- purchase order encumbrance
audience: Application User
ms.search.region: France
---

# (FRA) Process purchase order encumbrances and commitments at year end (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before beginning the year-end process for purchase orders and commitments, review [Process purchase orders at year end](process-purchase-orders-at-year-end.md). This topic explains the differences between the process as described there and the process used by public sector entities in France.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>Commitments are available only if the following conditions are met: 
> <UL>
> <LI>
> <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
> <LI>
> <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
> <LI>
> <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <STRONG>Commitments (France)</STRONG> regulatory document type is selected in the <STRONG>Budget parameters</STRONG> form, when the following hotfix is installed: KB3047235</P>
> <LI>
> <P>In cumulative update 7 for Microsoft Dynamics AX 2012, the <STRONG>Use French public sector accounting rules</STRONG> check box is selected in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>
> <P>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P>



## Prerequisites

Before you start the year-end process, make sure that the following prerequisites have been set up:

  - Enable budget control.

  - Enable both the encumbrance and pre-encumbrance processes.

  - Set up posting definitions.

  - Assign posting definitions to transaction posting types.

For more information, see [Process purchase orders at year end](process-purchase-orders-at-year-end.md).

## Closing and opening steps

The closing steps when you process purchase orders at the end of a fiscal year are exactly as described in [Process purchase orders at year end](process-purchase-orders-at-year-end.md). There is one addition to the opening steps from what is described in that topic. After the closing entries are reversed, budget reservations are created or updated in commitment documents in the new fiscal year. This is handled by the process. No manual intervention is required.

## Closing commitments

After you have processed purchase orders and commitments, the commitments in the closing fiscal year must be closed.

1.  Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Commitment close**.

2.  Click **Retrieve** to retrieve all open commitments that have a balance larger than zero.

3.  Review all the commitments in the grid. Select all commitments that you want to close as part of your year-end process.
    
    If you have already created commitments for the new fiscal year, they will be included in the grid. Be sure they are not selected for closing.

4.  Click **Process** to close all selected commitments.
    

    > [!WARNING]
    > <P>Closing a commitment line cannot be reversed. If you close a commitment line by mistake, you must create a new commitment to restore the budget reservation.</P>



## See also

[Encumber purchase orders](encumber-purchase-orders.md)

[Process purchase orders at year end](process-purchase-orders-at-year-end.md)

[Purchase order year-end process (form)](https://technet.microsoft.com/library/hh209522\(v=ax.60\))

[(FRA) Key tasks: Commitments (Public sector)](fra-key-tasks-commitments-public-sector.md)

  


