---
title: Pick an item
TOCTitle: Pick an item
ms:assetid: cc3d40cc-ec23-4f79-b010-865ee00adc93
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213668(v=AX.60)
ms:contentKeyID: 36059449
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Pick
- consolidated picking
- order picking
---

# Pick an item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

You can pick items using either order picking or consolidated picking.

Order picking is the basic way to handle item picking—one picking list is created for each order.

Consolidated picking combines multiple orders into one picking list. The orders can potentially be of different types; for example, they can include sales orders or transfer orders.

## Pick an item using order picking

Whether the items to be picked are for a sales order, a transfer order, or a production order, the same picking process can be used.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **Open sales orders**. Select a sales order, click the **Pick and pack** tab \> **Picking list** to print the picking list for a list of items to be picked from inventory.
    
    The order type will differ, depending on its origin.
    

    > [!NOTE]
    > <P>The picking list can be printed and the picking process started, even if all items are not in stock. This is useful if items are expected to arrive in stock before the picking process has been completed.</P>



2.  Pick the items from the inventory.
    

    > [!TIP]
    > <P>Use the printed picking list to verify any discrepancies in the number of items or the picking location.</P>



3.  Click **Inventory management** \> **Periodic** \> **Picking list registration**.
    

    > [!NOTE]
    > <P>The <STRONG>Picking list registration</STRONG> is also available from the <STRONG>Sales order</STRONG> or <STRONG>Transfer orders</STRONG> form.</P>



4.  Register the items that have been picked.

## Pick an item using consolidated picking

You can use the **Picking list** form or the **Picking list registration** form to pick an item using the consolidated picking process.


> [!NOTE]
> <P>See <A href="picking-methods.md">Picking Methods</A> for setup information.</P>



  - Use the **Picking list** form for consolidated guided picking where the route is sorted by location. For example, the nearest item is prioritized first, and the remaining items are prioritized according to proximity.

  - Use the **Picking list registration** form to confirm that items have been picked for sales orders, transfer orders, warehouse orders, or any other order references where picking registration is needed. This is the case when you use printed picking list.

<!-- end list -->

1.  Open the **Picking list registration** form. **Inventory management** \> **Periodic** \> **Picking list registration**.
    
    –or–
    
    Click **Inventory management** \> **Periodic** \> **Picking list registration**.
    
    –or–
    
    Click **Inventory management** \> **Periodic** \> **Transfer orders**. Click **Posting** \> **Picking list registration**.
    

    > [!NOTE]
    > <P>Details regarding each picking line are displayed in the <STRONG>Lines</STRONG> section of the form. In the <STRONG>Order picking overview</STRONG> section, information about all the lines for one order are displayed. Order picking has one picking list for each order.</P>

    
    Use the **Consolidated picking** and **Order picking** fields to filter on picking routes, based on one picking method. Use the **Picking route** field to filter on a specific picking route or on the bar code associated with the picking route.

2.  Click the **Functions** button to open a menu with the following options:
    
      - **Activation** – Activate the picking route if the picking route has a **Registered** status. See [About shipment reservations](about-shipment-reservations.md) for more information.
    
      - **Start picking route** – Start picking on a picking route that has an **Activated** status.
    
      - **Cancel picking route** – Cancel the picking route. When a picking route is canceled, the picking list must be posted from the original document, such as a sales order or transfer order.
    
      - **Deliver picked items** – Deliver the picked items to the location. It is possible to deliver items from a partially picked picking list to the staging area.
        

        > [!NOTE]
        > <P>For more information about locations see <A href="about-locations.md">About locations</A>.</P>

    
      - **Open output orders** – View open output orders for the picking route. The **Lines** tab contains the picking list lines that are associated with the picking list that can be updated or confirmed.
    
    The fields available to be updated in this section are **Location**, **Pallet ID**, and **Pick quantity**, if you have specified these dimensions to be displayed in the form. See [Specify inventory dimensions](specify-inventory-dimensions.md) for more information.

3.  Click the **Functions** button in the **Lines** section of the form for additional optional actions related to the pick line:
    
      - **Split** – If the complete quantity cannot be picked because of, for example, inventory shortage, spilt the line into two. Both lines will have the same lot ID.
        

        > [!NOTE]
        > <P>For sales orders that are listed on the picking list, splitting the picking line is possible only if the customer allows for partial delivery.</P>

    
      - **Unpick** – For lines that have a handling status of **Complete**, register the items for the selected line that have been returned to inventory. For example, if items were picked and reported from the wrong batch or if the customer does not need the full picked quantity.
    
      - **Cancel picking line** – For lines that do not have a handling status of **Complete**, remove them from the picking list. If one or more lines have already been picked and the handling status for the lines is **Picked** or **Complete**, you cannot cancel the picking line.

4.  Click the **Updates** button to update the picking list lines to a status of **Picked** or **Complete**, if this has been set up as part of the outbound rules. See [Set up outbound rules](set-up-outbound-rules.md) for more information.

## See also

[Start picking routes](start-picking-routes.md)

[Picking list registration (form)](https://technet.microsoft.com/en-us/library/hh242808\(v=ax.60\))

[About picking routes](about-picking-routes.md)

[Picking methods](picking-methods.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

