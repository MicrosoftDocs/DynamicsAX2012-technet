---
title: (LTU) Enter transport information in transfer order
TOCTitle: (LTU) Enter transport information in transfer order
ms:assetid: 3aec34a7-4c27-47b0-b949-2815bce1ae96
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665060(v=AX.60)
ms:contentKeyID: 49386643
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LTU) Enter transport information in transfer order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can enter transportation information in a transfer order and reprint the packing slip.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Enter transport information

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Press CTRL+N to create a new transfer order, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Receive transfer order" in the Applications and Business Processes Help.</P>



3.  If the packing slip uses auto-numbering, select the **Packing slip auto numbering** check box.
    

    > [!NOTE]
    > <P>You must enter the packing slip number manually if you do not select the <STRONG>Packing slip auto numbering</STRONG> check box.</P>



4.  Click the **Transportation details** tab.

5.  In the **Date** and **Time** fields, enter the date and time when the transfer order was created.

6.  In the **Created** field, enter the place where the transfer order was created.

7.  In the **Model** field, select the model of the transportation vehicle.

8.  In the **Registration number** and **Trailer registration number** fields, enter the registration number of the vehicle and of the trailer.

9.  In the **Carrier type** field, select **Customer**, **Vendor**, or **Invoice account** as the carrier.

10. In the **Carrier** field, select the account number of the carrier.
    

    > [!NOTE]
    > <P>This field is active only if <STRONG>Customer</STRONG> or<STRONG>Vendor</STRONG> is selected in the <STRONG>Carrier type</STRONG> field.</P>



11. In the **Driver** field, select the driver of the vehicle.
    

    > [!NOTE]
    > <P>The name of the selected driver is displayed in the <STRONG>Name</STRONG> field.</P>



12. In the **Transportation properties** fast tab, select the **Print transportation details** check box to print the transportation information on the invoice report.

13. In the **Goods issued by** field, select the name of the person who is responsible for issuing the load for transport.

14. In the **Package** field, enter a short description of the item.

15. In the **Risk level of the load** field, enter the danger level in degrees for the packaged item.

16. Click **Posting** \> **Ship transfer order** to open the **Shipment** form.

17. In the **Numbering** field, select the numbering code.

18. Select the **Print transfer shipment** check box to print the transfer shipment slip, and then click **OK** to post and print the packing slip.

## Reprint the packing slip

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Click **Print** \> **Packing Slip** to reprint the packing slip.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

