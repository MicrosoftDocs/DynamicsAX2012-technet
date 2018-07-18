---
title: (LTU) Document the internal transfer of items
TOCTitle: (LTU) Document the internal transfer of items
ms:assetid: 559be693-158d-4923-a93b-dc752bc5216e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665087(v=AX.60)
ms:contentKeyID: 49386669
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Document the internal transfer of items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to document the internal transfer of items from one location to another location. The two-step process requires that you specify the loading and destination warehouses, and that you enter information about how the items are transported.

## Specify the lading and unlading warehouses

1.  Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**.

2.  Select the warehouse, and then click the **Address** FastTab.

3.  Click **Add** to create an address.

4.  In the **New address** form, in the **Purpose** field, select one of the following options:
    
      - **Lading** – Select this option to specify the warehouse that the items are being transferred from.
    
      - **Unlading** – Select this option to specify the warehouse that the items are being transferred to.
        

        > [!NOTE]
        > <P>The lading and unlading addresses are displayed on a transfer order packing slip as the <STRONG>Loaded</STRONG> and <STRONG>Destination</STRONG> addresses.</P>



5.  On the **Address** and **Contact information** FastTabs, enter the address and contact information.

## Create a transfer order and specify transportation information

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Click **New** to create a transfer order.

3.  To automatically create numbers for packing slips, select the **Packing slip auto numbering** check box. To enter the number manually, clear the check box.

4.  In the **From warehouse** and **To warehouse** fields, select the lading and unlading warehouses.

5.  Click **Transportation details**.

6.  Select the **Print transportation details** check box to print the transportation information on the packing slip.

7.  In the **Goods issued by** field, select the name of the worker who is responsible for issuing the load for transport.

8.  In the **Package** field, enter a short description of the item.

9.  In the **Risk level of the load** field, enter the danger level for the packaged item.

10. In the **Carrier type** field, select the carrier.

11. In the **Carrier** field, select the account number for the carrier.
    
    You can select a carrier only if **Customer** or **Vendor** is selected in the **Carrier type** field.

12. In the **Model** field, select the model of the transportation vehicle.

13. In the **Registration number** and **Trailer registration number** fields, enter the registration numbers of the vehicle and the trailer.

14. In the **Driver** field, select the worker who is the driver of the vehicle. The name of the selected driver is displayed in the **Driver name** field.

15. In the **Document  date and time** field, enter the date and time when the items were loaded.

16. Close the **Transportation details** form.

17. In the **Transfer orders** form, click **Posting** \> **Ship transfer order**.

18. In the **Packing slip** field, enter or select the packing slip to post.

19. Select the **Print transfer shipment** check box, and then click **OK** to post the packing slip.

## Reprint the packing slip

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Click **Print** \> **Packing slip**.

## See also

[Transfer orders (form)](https://technet.microsoft.com/en-us/library/aa634530\(v=ax.60\))

  


