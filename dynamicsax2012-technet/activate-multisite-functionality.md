---
title: Activate multisite functionality
TOCTitle: Activate multisite functionality
ms:assetid: 6556a4c9-0f16-4ddf-95f7-1cfd85f9baac
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242191(v=AX.60)
ms:contentKeyID: 36056586
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- site
- location
- multisite
---

# Activate multisite functionality 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you upgrade to Microsoft Dynamics AX 2012, you must activate the multisite functionality for all company accounts before you upload your upgrade framework XPO file. The method you use to activate multisite functionality depends on the source system, and whether the **Trade** and **Logistics** licenses and configuration keys are enabled.

This topic contains information about the following upgrade scenarios:

  - Activate multisite functionality when you upgrade from Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012.

  - Activate multisite functionality when you upgrade from Microsoft Dynamics AX 4.0 to Microsoft Dynamics AX 2012.

  - **Trade** and **Logistics** licenses after you upgrade.

## Activate multisite functionality when you upgrade from Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012

When you upgrade from version Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012, use the **Multisite activation wizard** to activate multisite functionality for each account before you start the upgrade process.


> [!IMPORTANT]
> <P>You must activate multisite functionality before you load the upgrade framework XPO file. Otherwise, you will experience problems when you run the <STRONG>Multisite activation wizard</STRONG>.</P>



The wizard changes the following inventory dimension settings to support the use of the multisite functionality:

  - The site dimension and warehouse dimension become active in all inventory dimension groups.

  - The site dimension becomes mandatory, and a site value must appear on all inventory transactions.

  - A warehouse value must be entered on all issues and receipts. Blank issues and receipts are not allowed for the warehouse dimension.


> [!NOTE]
> <P>To identify any transaction-related issues that will prevent the multisite functionality from being activated, you may run the <STRONG>Multisite activation readiness</STRONG> report.</P>




> [!NOTE]
> <P>To perform this task, the LogisticsAdvanced configuration key must be enabled. If the configuration key is not enabled, activation will occur in the same way as when you upgrade from Microsoft Dynamics AX 4.0.</P>



1.  Click **Administration** \> **Reports** \> **System** \> **Multisite activation readiness** to open the report.

2.  In the **Site** field, select a site, or enter a site, to set as the default site to use when no warehouse is associated with a transaction. If a default site is stored in the database for this company, the field may be populated with the stored value, but you can override it.

3.  In the **Warehouse** field, enter the name of a new warehouse to set as the default warehouse to use when no warehouse is associated with a transaction. If a default warehouse is stored in the database for this company, the field may be populated with the stored value, but you can override it.
    

    > [!NOTE]
    > <P>The warehouse name that you enter must be new: The warehouse name must not exist and must never have existed. There cannot be any existing transactions that reference the warehouse name that you enter here. If these conditions are not met, the program displays an error message, and the report is not generated.</P>



4.  Select whether to generate the report directly or in batch.

5.  Click **OK**.

More information about how to prepare master data in Microsoft Dynamics AX 2009 for multisite functionality, and how to use the **Multisite activation wizard**, is available in the following topic:

  - [About sites and the multisite functionality](about-sites-and-the-multisite-functionality.md)

## Activate multisite functionality when you upgrade from Microsoft Dynamics AX 4.0 to Microsoft Dynamics AX 2012

When you upgrade from Microsoft Dynamics AX 4.0 to Microsoft Dynamics AX 2012, use the **Activate multisite** item on the **Preprocessing upgrade checklist** to activate the multisite functionality. During the upgrade, the script assigns a default site for warehouses, work centers, and so on, and the multisite functionality is activated in all companies. All transactions are associated with a site based on the warehouses and work centers that the transactions are assigned to.


> [!IMPORTANT]
> <P>Before you upgrade, if you are using virtual companies you must make the following changes to their configuration:</P>
> <UL>
> <LI>
> <P>Make sure that the inventory dimensions table is not shared.</P>
> <LI>
> <P>Make sure that tables that contain inventory dimension fields are not shared.</P></LI></UL>
> <P>Dimension group settings and data inconsistencies can prevent multisite functionality from becoming active. Under these circumstances, when you active the multisite functionality it can cause changes in the calculated item cost.</P>
> <P>If a production order spans multiple sites, the order must be closed before multisite is activated in order to maintain accurate cost information. For example, on a purchase order line for 100 T-shirts, 50 T-shirts are received in one warehouse and 30 T shirts in another. If these warehouses are on different sites, multisite cannot be activated until that purchase order line is closed. If you do not close the purchase order line, the cost may be incorrect.</P>



## Trade and Logistics licenses after you upgrade

When you upgrade to Microsoft Dynamics AX 2012, and the **Trade** license and associated configuration keys are enabled, the functionality associated with the **Logistics** license is also enabled.

## See also

[Create sites](create-sites.md)

[Set up site and warehouse hierarchies](set-up-site-and-warehouse-hierarchies.md)

[Set up fallback warehouses for sites](set-up-fallback-warehouses-for-sites.md)

[Set up a production unit](set-up-a-production-unit.md)

[About mandatory inventory dimensions](about-mandatory-inventory-dimensions.md)

  


