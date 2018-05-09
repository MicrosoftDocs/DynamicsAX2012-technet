---
title: Country/Regional specific features configuration key (CRSECountry)
TOCTitle: Country/Regional specific features configuration key (CRSECountry)
ms:assetid: b894a4e6-dec9-407e-b764-7f768ae80116
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa598692(v=AX.60)
ms:contentKeyID: 36997767
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Data_Dictionary.Configuration_Keys.CRSECountry
---

# Country/Regional specific features configuration key (CRSECountry) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Country/Regional specific features** configuration keys have been deprecated in Microsoft Dynamics AX 2012. In Microsoft Dynamics AX 2012, country/region context has replaced country/region configuration keys as the method for enabling control over country/region feature availability. Country/region configuration keys are still found in the Application Object Tree (AOT) and in the **License configuration** form. However, if you enable or disable a country/region configuration key, Microsoft Dynamics AX features are not enabled or disabled. This behavior might vary in partner-provided solutions.

Microsoft Dynamics AX uses the country/region of the primary address of the legal entity to control location-specific feature availability. For example, if the legal entity’s primary address in the **Legal entities** form is in Canada, users can see and work with features that are specific to Canada. For information about how to set up a legal entity in Microsoft Dynamics AX, see [Legal entities (form)](https://technet.microsoft.com/en-us/library/hh242860\(v=ax.60\)).

## See also

[Multiple countries/regions configuration key (CRSEMultiple)](multiple-countries-regions-configuration-key-crsemultiple.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

