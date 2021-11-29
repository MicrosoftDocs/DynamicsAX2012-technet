---
title: About warehouse management journal names
TOCTitle: About warehouse management journal names
ms:assetid: 766118a6-b4db-4ce0-8b0f-428a796ae5ed
ms:mtpsurl: https://technet.microsoft.com/library/Aa550038(v=AX.60)
ms:contentKeyID: 36058191
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About warehouse management journal names 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

Use journals in **Inventory management** under **Journals** \> **Item arrival** to register the receipt of items. When a new journal is created, some of the information for the journals is retrieved from a journal name setup form. The journal name setup forms are referred to as the Journal names forms.

A journal name setup exists for the various journal types in Microsoft Dynamics AX. In the table below you can see the field information from the journal names for the **Inventory management** area. Information from the fields in the table below is copied to the **Item arrival** and **Production input** journals, where you can edit it.

## Default values

Use the default value check boxes to determine who controls the decision on the placement of inventory. These are found on **General** in the **Journal names, warehouse management** form under **Setup** \> **Journals** in **Inventory management**. The inventory referred to here is that received in the warehouse. When items are received at inbound docks, default values are used as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Pallet transports</strong></p></td>
<td><p>Select this check box to give the item the status of registered after the transport job has been completed.</p>
<p>Clear this check box to move the items to the new location automatically. This occurs when the journal is posted, not when the item is physically moved to the new location.</p></td>
</tr>
<tr class="even">
<td><p><strong>Check picking location</strong></p></td>
<td><p>Microsoft Dynamics AX checks picking locations to find a spot for received items.</p>
<p>If this check box and the <strong>Check bulk locations</strong> check box are both selected, the picking location is checked first.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Check bulk locations</strong></p></td>
<td><p>Microsoft Dynamics AX checks the bulk locations to find a spot for received items.</p></td>
</tr>
</tbody>
</table>


## Possible combinations

The **Default values** check boxes have three states:

  - All check boxes are cleared – Microsoft Dynamics AX does not generate location destinations for incoming items. Items are registered at the specified location. On the journal line, indicate the locations where the items are to be positioned.

  - The **Check picking location** check box or the **Check bulk locations** check box is selected. When either or both of the check boxes are selected, Microsoft Dynamics AX generates location destinations for incoming items. If both are selected, Microsoft Dynamics AX checks the picking location first. If that location is full, the bulk locations are checked.
    
    When the journal is posted, Microsoft Dynamics AX automatically selects the items that are to be on-hand at the new location immediately. The company determines the physical movement of items.
    

    > [!NOTE]
    > <P>Specify an inbound dock location on the journal.</P>



  - The **Pallet transports** check box is selected. Also, either or both of the **Pallet transports** and **Check bulk locations** check boxes are selected. Posting the journal means Microsoft Dynamics AX generates transport jobs to move pallets to system-generated locations. Pallets are not shown as moved and items are not shown as on-hand until the transport jobs are completed.
    

    > [!NOTE]
    > <P>Specify an inbound dock and a pallet ID on the journal line.</P>



## See also

[About pallet transports](about-pallet-transports.md)

[Register item receipts with an item arrival journal](register-item-receipts-with-an-item-arrival-journal.md)

  


