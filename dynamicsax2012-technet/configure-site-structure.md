---
title: Configure site structure
TOCTitle: Configure site structure
ms:assetid: 361745b4-edcf-4b04-acef-74895127a5eb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731775(v=AX.60)
ms:contentKeyID: 35132601
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure site structure 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to define a structure for your sites, warehouses, and resource groups. Additionally, you can specify the default site, warehouse, and the fallback warehouse to assign to transactions for which this information is not available and cannot be deduced.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## To configure the site structure

1.  Click the **Configure site structure** task to open the form with the same name.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  In the **Filter by company** field, select the company account for which you want to define a site structure.

4.  In the **Site** field, enter a unique identifier for the site.

5.  In the **Name** field, enter the name of the site.

6.  To assign a warehouse or resource to this site, click the **Warehouses** or **Work center groups** tab, and then select the site in the **Site** field.

7.  To specify the default site, warehouse, and fallback warehouse for this site, click the **Defaults** tab and then select the site in the **Default site**, **Default warehouse**, or **Fallback warehouse** field.

## See also

[Configure site structure (form)](https://technet.microsoft.com/en-us/library/hh202081\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

