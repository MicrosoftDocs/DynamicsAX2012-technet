---
title: (FRA) About commitments (Public sector)
TOCTitle: (FRA) About commitments (Public sector)
ms:assetid: f3fe899a-93bd-40b9-bd81-c243d7f0f658
ms:mtpsurl: https://technet.microsoft.com/library/Hh208606(v=AX.60)
ms:contentKeyID: 36056396
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- commitments
- public sector
- commitment
- France
- French
audience: Application User
ms.search.region: France
---

# (FRA) About commitments (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Commitments are used to reserve budgeted amounts so that an organization can explicitly track budget reservations for management and reporting throughout the expenditure cycle. When commitments are used as part of the budgeting process, each purchase agreement, purchase order, and vendor invoice is associated with at least one commitment. The commitment is relieved when the purchase order is confirmed or when funds are released from the purchase agreement. When an invoice does not reference a purchase order or purchase agreement, the commitment associated with the invoice is relieved when the invoice is posted.

In addition, a commitment may specify a vendor. When a vendor is specified, any purchase order, purchase agreement, or vendor invoice that references the commitment must have the same vendor.


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



## Using commitments

To create commitments, you must activate the budget control configuration, turn on budget control, and confirm an original budget. For more information, see [(FRA) Key tasks: Commitments (Public sector)](fra-key-tasks-commitments-public-sector.md).

Commitments are valid from the date they are created through the end of the fiscal year or until they are closed. Commitments cannot be carried over from one fiscal year to the next. For more information, see [(FRA) Process purchase order encumbrances and commitments at year end (Public sector)](fra-process-purchase-order-encumbrances-and-commitments-at-year-end-public-sector.md).

## See also

[(FRA) Commitment (form) (Public sector)](https://technet.microsoft.com/library/hh208609\(v=ax.60\))

[(FRA) Commitment close (form) (Public sector)](https://technet.microsoft.com/library/hh208596\(v=ax.60\))

[Budgeting](budgeting.md)

  


