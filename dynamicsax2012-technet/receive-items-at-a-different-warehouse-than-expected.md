---
title: Receive items at a different warehouse than expected
TOCTitle: Receive items at a different warehouse than expected
ms:assetid: f58cffbc-56ee-473c-b7b8-44ac77e733c8
ms:mtpsurl: https://technet.microsoft.com/library/Dn887226(v=AX.60)
ms:contentKeyID: 63378894
author: Khairunj
ms.date: 11/13/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Receive items at a different warehouse than expected 


[!INCLUDE[archive-banner](includes/archive-banner.md)]



> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



The features described in this topic are only available if you have installed Microsoft Dynamics AX 2012 R3 Cumulative Update 8. This topic describes what’s required for setting up a mobile device to receive loads or items at a warehouse that differs from the warehouse that was specified on the source document. When you receive the load or item, the load or item is located at the new warehouse and all related work is created for the new warehouse. This means that all processes for managing the inventory are the same as they would have been at the warehouse where the inventory was expected, this includes packing structures and advanced shipping notices. The information on the source document is not changed to reflect the new warehouse.

This feature has the following limitations:

  - The warehouse must be assigned to the same site that was specified on the source document.

  - Inbound workflows on the mobile device for purchasing and returns only support the following work creation processes:
    
      - **License plate receiving**
    
      - **Purchase order line receiving**
    
      - **Purchase order line receiving and put away**
    
      - **Purchase order item receiving**
    
      - **Purchase order item receiving and put away**
    
      - **Return order receiving**
    
      - **Return order receiving and put away**
    
      - **Load item receiving**
    
      - **Load item receiving and put away**


> [!WARNING]
> <P>If you enable this feature, to avoid mistakes it’s important that the worker who is receiving the load or items ensures that they are logged on to the correct warehouse. For example, if a worker is working in Warehouse A, but has forgotten that he is logged on to his mobile device in Warehouse B, the load or items will be mistakenly located at Warehouse B.</P>



To enable receipts at a warehouse that differs from the warehouse on the source document, in the **Sites** form, on the **Warehouse management** tab, select the **Allow users on mobile devices to receive at another warehouse** check box.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>


## See also

[Configure mobile devices for warehouse work](configure-mobile-devices-for-warehouse-work.md)

[Create or modify an inbound load](create-or-modify-an-inbound-load.md)

  


