---
title: (FRA) About titres de recette (Public sector)
TOCTitle: (FRA) About titres de recette (Public sector)
ms:assetid: 1550611c-ed0e-4d81-948e-31f52b74d127
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh450742(v=AX.60)
ms:contentKeyID: 36966680
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- France
- French
- titre
- titre de recette
- titres
- titres de recette
---

# (FRA) About titres de recette (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The titre de recette is used by the director to notify the accountant that the organization is entitled to collect a specific amount from another entity, and to authorize the accountant to collect that amount. The titre maintains the strict separation that is required between the operational role of the director and the accounting role of the accountant.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>Titres de recette are available only if the following conditions are met: 
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



In Microsoft Dynamics AX, each titre is assigned a single free text invoice line. This guarantees that each titre concerns only one type of revenue and includes only one budgetary account.

A group of related titres, together with all supporting documentation, are assigned to a bordereau de titre for submittal to the accountant. The director must make sure that the bordereau de titre includes either operating revenue or capital revenue. It cannot include a mix.


> [!IMPORTANT]
> <P>A titre cannot be assigned a customer invoice that was entered through the payment journal.</P>



## See also

[(FRA) Maintain titres de recette (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh450748\(v=ax.60\))

[(FRA) Key tasks: Titres de recette and bordereaux de titre (Public sector)](fra-key-tasks-titres-de-recette-and-bordereaux-de-titre-public-sector.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

