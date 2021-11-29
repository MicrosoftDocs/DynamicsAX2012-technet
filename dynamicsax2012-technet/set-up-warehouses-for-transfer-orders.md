---
title: Set up warehouses for transfer orders
TOCTitle: Set up warehouses for transfer orders
ms:assetid: fccc4095-ab94-4e3f-8370-5d3e79aab5c1
ms:mtpsurl: https://technet.microsoft.com/library/Aa500101(v=AX.60)
ms:contentKeyID: 36060098
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- master planning and transfer orders
- refilling warehouse
- warehouse levels
- transfer orders between warehouses
- transfer orders
- transfer requirement
audience: Application User
ms.search.region: Global
---

# Set up warehouses for transfer orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use warehouse levels to create a hierarchy that supports transfer orders between warehouses. Based on this setup, master scheduling calculates item requirements at the individual warehouse level and generates planned transfer orders from an assigned source warehouse to fulfill them.

1.  Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**.

2.  Select the warehouse that you want to refill.

3.  On the **Master planning** FastTab, select the **Refilling** check box.

4.  In the **Main warehouse** field, select the warehouse that you want to assign as the refilling warehouse. Master scheduling calculates a transfer requirement for the selected warehouse and generates a planned transfer order from the assigned **Main warehouse**.
    

    > [!NOTE]
    > <P>If you clear the <STRONG>Refilling</STRONG> check box, the selected warehouse is assigned a warehouse level with regard to the <STRONG>Main warehouse</STRONG>, but the <STRONG>Main warehouse</STRONG> is not set up as a refilling warehouse.</P>



5.  Close the form to apply the new setup.


> [!TIP]
> <P>If you want to assign a warehouse for refilling, you must first set up the warehouse as a storage dimension in the <STRONG>Storage dimension groups</STRONG> form. In this form, select the <STRONG>Active</STRONG> field and the <STRONG>Coverage plan by dimension</STRONG> field for the warehouse.</P>



## See also

[Warehouses (form)](https://technet.microsoft.com/library/aa620570\(v=ax.60\))

  


