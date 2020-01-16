---
title: (LTU) Correct a packing slip
TOCTitle: (LTU) Correct a packing slip
ms:assetid: 6ee9bdf3-40aa-40ce-8d5a-1faa969a47bc
ms:mtpsurl: https://technet.microsoft.com/library/JJ665110(v=AX.60)
ms:contentKeyID: 49386692
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Correct a packing slip 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If a packing slip document is incorrect, you must create a reverse transfer order, change the document status, and reset its dependence to the packing slip register.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Press CTRL+N to create a new transfer order, and enter the required details.
    

    > [!NOTE]
    > <P>You must set up the transit warehouse with the location.</P>



3.  In the **Ship now** tab (lower pane), enter the **Ship now** amount.

4.  Click **Posting** \> **Ship transfer order** to open the **Shipment** form. Enter the required details.

5.  Enter or modify the packing slip number in the **Packing slip** field.

6.  Select the **Edit lines** check box, to modify the line details.

7.  Click **OK**.

8.  In the **Transfer orders** form, click **Posting** \> **Receive** and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Receive Transfer order" in the Applications and Business Processes Help.</P>



9.  Click **OK** or close the form.
    

    > [!NOTE]
    > <P>In the <STRONG>Transfer order</STRONG> form, the transfer status is changed to <STRONG>Received</STRONG>.</P>



10. Press CTRL+N to create a reverse transfer order, and then enter the required details in the **Transfer orders** form.

11. Repeat steps 3 and 4.

12. Select the transfer order, and then click **Inquiries** \> **Transfer order history**.

13. Select the shipment or receiving document, and then click **Functions** \> **Change status**.
    

    > [!NOTE]
    > <P>In the <STRONG>Document status</STRONG> field, the existing document status is displayed.</P>



14. In the **New Document status** field, select the new document status as **Canceled** or **Broken**. Close the form.

15. Select the transfer order, and then click **Inquiries** \> **Transfer order history**.

16. If the document is a packing slip register, select the shipment or receiving document, and then click **Change dependences to Packing slip register**.

17. Click **OK** to change the dependence to the packing slip register.

  


