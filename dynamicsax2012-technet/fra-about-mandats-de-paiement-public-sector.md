---
title: (FRA) About mandats de paiement (Public sector)
TOCTitle: (FRA) About mandats de paiement (Public sector)
ms:assetid: adc03bf5-593c-430e-963a-e0cd45806f83
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh450747(v=AX.60)
ms:contentKeyID: 36966685
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- Public sector
- France
- French
- mandat
- mandat de paiement
- mandats
- mandats de paiement
audience: Application User
ms.search.region: France
---

# (FRA) About mandats de paiement (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The mandat de paiement is used by the director to notify the accountant that the organization is obligated to pay a specific amount to another entity, and to authorize the accountant to pay that amount. The mandat maintains the strict separation that is required between the operational role of the director and the accounting role of the accountant.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>Mandats de paiement are available only if the following conditions are met: 
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



In Microsoft Dynamics AX, each mandat is assigned a single vendor invoice line. This guarantees that each mandat concerns only one creditor and includes only one budgetary account.

A group of related mandats, together with all supporting documentation, are assigned to a bordereau de mandat for submittal to the accountant. The director must make sure that the bordereau de mandat includes either operating expenses or capital expenses. It cannot include a mix.

## See also

[(FRA) Maintain mandats de paiement (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh450744\(v=ax.60\))

[(FRA) Key tasks: Mandats de paiement and bordereaux de mandat (Public sector)](fra-key-tasks-mandats-de-paiement-and-bordereaux-de-mandat-public-sector.md)

  


