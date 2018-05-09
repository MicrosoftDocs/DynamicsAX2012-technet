---
title: Change the reservation on a single order
TOCTitle: Change the reservation on a single order
ms:assetid: 83629914-bf07-4d2f-bef2-c66d766ab7f5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571561(v=AX.60)
ms:contentKeyID: 37832515
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Change the reservation on a single order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

When changing a reservation, you can either change the quantity, cancel the reservation or you can change the reservation by dimensions.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select the order for which the reservations should be changed, click **Edit**, and then select the appropriate order line.

3.  Click **Inventory** \> **Reservation**.

4.  On the **Overview** tab, you can change the quantity of the reservation or cancel the reservation.
    
      - To change the reserved quantity, change the quantity in the **Reservation** field.
    
      - To cancel the reserved quantity, change the quantity in the **Reservation** field to zero.

## Change a reservation by dimensions

When you change reservations by dimensions, you can either specify that an existing reservation should be for specific dimensions or you can change the dimensions of the reservation.


> [!NOTE]
> <P>When you reserve a quantity of an item, you can only reserve on dimensions that are active for the item.</P>



1.  Open the **Reservation** form by following the preceding guidelines, and select the line where you want to change the dimensions of a reservation.

2.  Click **Inventory** \> **Dimensions display** and in the **Dimensions display** form, select the check boxes for the dimensions that you want to either specify or change.
    
    Lines are displayed on the **Overview** tab in the **Reservation** form for each of the existing dimension combinations of the order line.

3.  Select the line for the dimension combination where you want to either reserve a quantity or change the reserved quantity.

4.  Change the quantity in the **Reservation** field.


> [!NOTE]
> <P>When you display a specific dimension combination in the <STRONG>Reservation</STRONG> form and then edit or enter a quantity in the <STRONG>Reservation</STRONG> field, the reservation is locked to the selected dimensions and the reserved quantity is dedicated to these dimensions. You can unlock dimensions by clearing the check boxes under <STRONG>Lock reservations</STRONG>.</P>
> <P>If <STRONG>Primary stocking</STRONG> is specified for an item via the product dimension group, the dimension is always locked and it cannot be unlocked.</P>



## Example

A customer calls with a request concerning a load of bricks that they have ordered from your company. The customer wants to make sure that the bricks are reserved from the same batch as the previous load that they received. When checking, you observe that the bricks are reserved automatically with no batch number specified on the sales order line so you need to make sure that the reserved quantity has the correct batch number and that the reservation is locked with this batch number.

1.  Select the sales order of the ordered brick load in the **Sales order** form and open the **Reservation** form.

2.  Apply one of the following methods depending on whether the bricks have been automatically reserved with the correct batch number or not. If the batch number is correct, you just need to lock the batch number reservation to ensure that the batch number is not changed by an automated process. To lock the batch number, do the following:
    
    1.  Select the reservation in the **Reservation** form.
    
    2.  Click **Inventory** \> **Dimensions display**.
    
    3.  Select the **Batch number** check box, and click **OK**.
    
    4.  Select the **Batch number** check box under **Lock reservations**.

3.  To change the batch number dimension of the reservation, do the following:
    
    1.  Click **Inventory** \> **Dimensions display**, select the **Batch number** check box, and click **OK**.
    
    2.  Select the existing reservation in the **Reservation** form, and change the quantity in the **Reservation** field to zero to cancel this reservation line.
    
    3.  Select the line with the batch number dimension that the customer requested and enter the quantity in the **Reservation** field.

## See also

[Reserve inventory quantities](reserve-inventory-quantities.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

