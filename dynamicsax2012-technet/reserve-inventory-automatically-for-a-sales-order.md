---
title: Reserve inventory automatically for a sales order
TOCTitle: Reserve inventory automatically for a sales order
ms:assetid: fa98af3d-7bd5-4c8e-8529-3de458a6db10
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa499864(v=AX.60)
ms:contentKeyID: 36060070
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- auto reservation
- automatic reservation
- inventory reservation
- reservation
audience: Application User
ms.search.region: Global
---

# Reserve inventory automatically for a sales order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

The procedure to reverse inventory automatically for a sales order applies in two situations.

  - **Automatic** is selected in the **Reservation** field on the **General** tab on the **Accounts receivable parameters** form.
    
    –or–

  - **Automatic** is selected in the **Reservation** field (**Setup** tab) on the order header of a specific order.

<!-- end list -->

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. From the **All sales orders** form, select an existing sales order or create a new sales order.

2.  From the **Sales order** form, create a sales order line.

3.  Enter quantity and other relevant data.

4.  Click **Inventory** \> **Reservation** to view and edit the reservations on the item.
    

    > [!NOTE]
    > <P>Inventory is reserved according to the setup of the <STRONG>Date-controlled</STRONG> reservation in the <STRONG>Item model groups</STRONG> form, and, eventually, in the warehouse of the customer account. By repeating step 4, you can change inventory reservations on items that are not delivered. You cannot reserve more than the quantity entered on the sales order line. If you increase or decrease the quantity on the sales order line, the reserved quantity is changed accordingly.</P>


  


