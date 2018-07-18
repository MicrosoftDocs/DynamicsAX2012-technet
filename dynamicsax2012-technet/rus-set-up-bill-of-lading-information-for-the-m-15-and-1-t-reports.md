---
title: (RUS) Set up bill of lading information for the M-15 and 1-T reports
TOCTitle: (RUS) Set up bill of lading information for the M-15 and 1-T reports
ms:assetid: 596dc400-73f1-4634-991f-16e22984019c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733230(v=AX.60)
ms:contentKeyID: 49685197
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up bill of lading information for the M-15 and 1-T reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can enter bill of lading information for the M-15 and 1-T reports that are generated for bailment.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Select a transfer order for bailment.

3.  Click the **General** tab, and then, in the **Type of transfer** field, select **Shipment to external party**.

4.  Click the **Bill of lading** tab, and then, in the **Carrier type** field, select the type of supplier from the following options:
    
      - **Invoice account** – The supplier is a third party.
    
      - **Customer** – The supplier is a customer.
    
      - **Vendor** – The supplier is a vendor.

5.  In the **Carrier** field, select the account number of the supplier.
    

    > [!NOTE]
    > <P>This field is available only if you selected <STRONG>Customer</STRONG> or <STRONG>Vendor</STRONG> in the <STRONG>Carrier type</STRONG> field.</P>



6.  In the **Type** field, select the type of license card that the driver has.

7.  In the **Registration number**, **Series**, and **Number** fields, enter the license card registration number, license card series, and license card number of the driver.

8.  In the **Delivery date** and **Model** fields, select the date when the items are delivered and the model of the vehicle that is used to ship the items.

9.  In the **Registration number** and **Waybill** fields, enter the registration number of the vehicle and the waybill number of the shipment. A waybill is a document that is prepared by the carrier of a shipment of items. The waybill contains details of the shipment, route, and charges.

10. In the **Driver's name** and **Driving license** fields, enter the name and license number of the driver.

11. In the **Type** and **Driver** fields, select the type of transportation for bailment and the identification code of the driver. You can also view or modify the bill of lading information on the **Bill of lading** tab in the **Shipment** form.
    

    > [!NOTE]
    > <P>In the <STRONG>Lading address</STRONG> and <STRONG>Unlading address</STRONG> fields, the loading and unloading addresses for the items are updated based on the warehouses that are selected in the <STRONG>From warehouse</STRONG> and <STRONG>To warehouse</STRONG> fields on the <STRONG>Overview</STRONG> tab.</P>



## See also

[Transfer orders (form)](https://technet.microsoft.com/en-us/library/aa634530\(v=ax.60\))

[About transfer orders](about-transfer-orders.md)

  


