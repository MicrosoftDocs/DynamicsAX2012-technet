---
title: About configuration rules
TOCTitle: About configuration rules
ms:assetid: 22a7bd30-7fc4-46d3-9e6d-47b2e403d966
ms:mtpsurl: https://technet.microsoft.com/library/Aa496798(v=AX.60)
ms:contentKeyID: 36676374
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- configuration rules
- configuration variants
- define configurations
audience: Application User
ms.search.region: Global
---

# About configuration rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Configuration rules are applied to each new configuration variant that you select in the **Define new configurations or choose between existing configurations.** dialog box. Configuration rules prevent item number from being incorrectly selected. They also make it easier to define configurations, because an item number that is directly linked to another item number is automatically selected as a connected unit in system transactions.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



Existing configurations are not affected by subsequent changes to the configuration rules. However, it is important to set the rules before you define a new configuration, or to check them if you think the rules have been changed.


> [!NOTE]
> <P>The method <STRONG>Select</STRONG> means that the derived configuration group, item number, and configuration are automatically selected. The method <STRONG>Deselect</STRONG> means that the derived configuration group, item number, and configuration cannot be selected.</P>



You can use configuration rules to direct a configuration group and item number to automatically select an associated item number in another configuration group, or you can use them to prohibit a configuration group and an item number from selecting a particular item number in another configuration group.

## See also

[Product Builder configuration (form)](https://technet.microsoft.com/library/aa571726\(v=ax.60\))

  


