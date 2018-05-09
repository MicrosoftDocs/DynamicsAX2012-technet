---
title: (RUS) Create and post a sales order that has transportation invoice and job ticket details
TOCTitle: (RUS) Create and post a sales order that has transportation invoice and job ticket details
ms:assetid: cfb3b4da-ff65-4f96-9459-82b993975039
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711626(v=AX.60)
ms:contentKeyID: 49387950
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a sales order that has transportation invoice and job ticket details 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to generate and print a transportation invoice or a job ticket that is based on a bill of lading for a sales order. For more information, see [(RUS) About transportation invoices and job tickets that are based on bills of lading](rus-about-transportation-invoices-and-job-tickets-that-are-based-on-bills-of-lading.md).

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order, and then click **Edit** to open the **Sales order** form.

3.  On the **Action Pane**, on the **Pick and pack** tab, in the **Generate** group, click **Packing slip**.

4.  In the **Packing slip posting** form, on the **Parameters** tab, select the **Transportation document** check box to print a transportation invoice or a job ticket for the sales order.

5.  On the **Bill of lading** tab, in the **Registration number**, **Series**, and **Number** fields, enter information for the license card.

6.  In the **Carrier type** field, select the type of carrier:
    
      - **Invoice account** – The carrier is the customer that is selected as the invoice account on the sales order.
    
      - **Customer** – The carrier is the customer account that is specified in the **Carrier** field.
    
      - **Vendor** – The carrier is the vendor account that is specified in the **Carrier** field.

7.  In the **Carrier** field, select the registration number of the carrier.
    
    This field is available only if you selected **Customer** or **Vendor** in the **Carrier type** field.

8.  In the **Delivery date** and **Model** fields, select the date of delivery and the model of the vehicle.

9.  In the **Registration number** and **Waybill** fields, enter the registration number and waybill number of the vehicle.

10. In the **Driver name**, **Driving license**, and **Driver contact data** fields, enter information about the driver.

11. In the **Type**, enter the type of transport.

12. In the **Document type** field, select **Transportation invoice** or **Job ticket**.

13. In the **Cargo description** and **Cargo packing** fields, enter information about the shipping description of the cargo.

14. Click **OK** to post and print the packing slip that includes the details from the transportation invoice or job ticket.

15. To post the invoice for the sales order, on the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

16. Repeat steps 4 through 13 to enter the details for the transportation invoice or job ticket. Then click **OK** to post and print the sales order invoice that includes the details from the transportation invoice or job ticket.

## See also

[Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

