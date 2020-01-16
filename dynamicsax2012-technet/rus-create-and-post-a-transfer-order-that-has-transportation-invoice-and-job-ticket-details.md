---
title: (RUS) Create and post a transfer order that has transportation invoice and job ticket details
TOCTitle: (RUS) Create and post a transfer order that has transportation invoice and job ticket details
ms:assetid: 2b351001-9efa-4d31-9a38-6196cde1938d
ms:mtpsurl: https://technet.microsoft.com/library/JJ665233(v=AX.60)
ms:contentKeyID: 49387322
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post a transfer order that has transportation invoice and job ticket details 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to create and post a transfer order that includes the details from the transportation invoice and job ticket. For more information, see [(RUS) About transportation invoices and job tickets that are based on bills of lading](rus-about-transportation-invoices-and-job-tickets-that-are-based-on-bills-of-lading.md).

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create a transfer order. For more information, see [About transfer orders](about-transfer-orders.md).

3.  Click the **Bill of lading** tab, and then, in the **Carrier type** field, select **Customer** or **Vendor**.

4.  In the **Carrier** field, select the registration number of the carrier.
    
    This field is available only if you selected **Customer** or **Vendor** as the carrier type.

5.  In the **Delivery date** and **Model** fields, select the date of delivery and the model of the vehicle.

6.  In the **Registration number** and **Waybill** fields, enter the registration number and waybill number of the vehicle.

7.  In the **Driver name**, **Driving license**, and **Driver contact data** fields, enter information about the driver.

8.  In the **Type** field, select the type of transport.

9.  In the **Driver** field, select the unique identification code for the designated driver of the vehicle.

10. In the **Document type** field, select **Transportation invoice** or **Job ticket**.

11. In the **Cargo description** and **Cargo packing** fields, enter information about the shipping description of the cargo.

12. Click **Posting** \> **Ship transfer order** to open the **Shipment** form.

13. Click the **General** tab, and then select the **Print transportation invoice** check box to print a transportation invoice or a job ticket.
    
    You can view the details of the transportation invoice or job ticket on the **Bill of lading** tab. The information that is displayed is based on the information that was entered in the **Transfer orders** form.

14. Click **OK** to post the transfer order.
    

    > [!NOTE]
    > <P>You can also use the <STRONG>Transfer order history</STRONG> form to generate a transportation document and a job ticket that are based on the transfer order. Click <STRONG>Inventory management</STRONG> &gt; <STRONG>Periodic</STRONG> &gt; <STRONG>Transfer orders</STRONG>. Click <STRONG>Inquiries</STRONG> &gt; <STRONG>Transfer order history</STRONG>.</P>
    > <P>You can also print a transportation invoice or a job ticket from the <STRONG>Bill of lading</STRONG> form. Click <STRONG>Inventory management</STRONG> &gt; <STRONG>Periodic</STRONG> &gt; <STRONG>Transfer orders</STRONG>. Click <STRONG>Inquiries</STRONG> &gt; <STRONG>Bill of lading</STRONG>.</P>



## See also

[Transfer orders (form)](https://technet.microsoft.com/library/aa634530\(v=ax.60\))

  


