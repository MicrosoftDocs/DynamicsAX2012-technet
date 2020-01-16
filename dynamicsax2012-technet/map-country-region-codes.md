---
title: Map country/region codes
TOCTitle: Map country/region codes
ms:assetid: 759aa0cb-bdba-4f3f-abf9-f859baa24a5c
ms:mtpsurl: https://technet.microsoft.com/library/Gg731832(v=AX.60)
ms:contentKeyID: 35132681
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Map country/region codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 4.0 and Microsoft Dynamics AX 2009, more than one country/region code could be assigned to a country/region. Only one country/region code per company from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 can be mapped to a country/region code in Microsoft Dynamics AX 2012. Before you upgrade to Microsoft Dynamics AX 2012, all country/region codes in your current version of Microsoft Dynamics AX must be mapped to a country/region code in Microsoft Dynamics AX 2012.

For example, in Microsoft Dynamics AX 4.0, you may have assigned the country/region code GBR to both Great Britain and the United Kingdom. Before you can upgrade to Microsoft Dynamics AX 2012, you must reassign the GBR code to one of those countries/regions and assign a new unique country/region code to the other country/region.

Use this form to map the country/region codes in all companies in Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 to the country/region codes in Microsoft Dynamics AX 2012. All country/region codes must be mapped from the earlier version to Microsoft Dynamics AX 2012.


> [!WARNING]
> <P>If your Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 application contains customized code that affects the handling of country/region data, you might encounter errors during data preprocessing. If you encounter these errors, you will need to write an upgrade preprocessing script to correctly map your existing data to the Microsoft Dynamics AX 2012 schema. For more information, see the white paper <A href="http://go.microsoft.com/fwlink/?linkid=212587%26clcid=0x409">How to Write Data Upgrade Scripts for Microsoft Dynamics AX 2012</A>.</P>



If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

1.  In the **Preprocessing upgrade checklist**, click **Map country/region codes** to open the **Country/region code mapping** form.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  For each country/region in the grid, in the **Mapped country/region** column, use the menu to select the Microsoft Dynamics AX 2012 country/region code that corresponds to the country/region code from your earlier version of Microsoft Dynamics AX. The country/region code from your earlier version is displayed in the **Country/region code** column.

4.  After you map all the country/region codes from the earlier version of Microsoft Dynamics AX to the country/region codes in Microsoft Dynamics AX 2012, click **Set to ready for upgrade**.

  


