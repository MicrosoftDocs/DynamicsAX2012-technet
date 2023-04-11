---
title: About purchase order upgrade
TOCTitle: About purchase order upgrade
ms:assetid: 697e8730-fb55-4cdd-9692-70a9304993c1
ms:mtpsurl: https://technet.microsoft.com/library/Gg731822(v=AX.60)
ms:contentKeyID: 35132670
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About purchase order upgrade 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you invoice in Microsoft Dynamics AX 2012, the accounting framework does not relieve any accounting entries for accruals that were generated in an earlier version of the program. To upgrade to Microsoft Dynamics AX 2012, you must first relieve any accrual entries that remain for purchase order quantities received but not yet matched to vendor invoices.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

To begin the upgrade, select the journal name. The journal name identifies the journal that make up the relief of accruals for purchase order quantities received but not yet matched to vendor invoices.


> [!NOTE]
> <P>Set these parameters in Microsoft Dynamics AX 2009 to ensure that accounting entries are generated. The accounting entries are generated for the accrual for purchase quantities received but not yet matched to vendor invoices:</P>
> <UL>
> <LI>
> <P>Set the <STRONG>Post packing slip to ledger</STRONG> field to <STRONG>True</STRONG> in the <STRONG>Accounts payable parameters</STRONG> form.</P>
> <LI>
> <P>Set the <STRONG>Post accrued expense</STRONG> field to <STRONG>True</STRONG> in the item's item model group.</P></LI></UL>


  


