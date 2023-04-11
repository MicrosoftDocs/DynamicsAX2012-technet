---
title: (BRA) Create an outbound transfer fiscal document
TOCTitle: (BRA) Create an outbound transfer fiscal document
ms:assetid: 5918ea0c-7e09-4527-a6ff-f9d520a8e0fc
ms:mtpsurl: https://technet.microsoft.com/library/JJ933519(v=AX.60)
ms:contentKeyID: 50935133
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- Transfer fiscal documents
- Create transfer orders
- outbound transfer fiscal documents
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create an outbound transfer fiscal document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can transfer items between warehouses that are located at the same or different fiscal establishments in the same company by using a transfer order. For more information, see [(BRA) About transfer orders](bra-about-transfer-orders.md). When you ship items to a warehouse that is located at a different fiscal establishment, or if the fiscal establishment is associated with a customer account or a vendor account, an outbound transfer fiscal document is issued.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  In the upper pane, click **New** to create a transfer order.

3.  In the **From warehouse** and **To warehouse** fields, select the originating warehouse and destination warehouse for the transfer of items.
    
    The **Order type** field is updated based on the values that you select in the **From warehouse** and **To warehouse** fields.

4.  On the **Fiscal information** tab, specify values in the following fields:
    
    1.  In the **Fiscal document type** field, update the type of fiscal document for the transfer fiscal document.
    
    2.  In the **Carrier name** field, select the name of the carrier that transports the items.
    

    > [!NOTE]
    > <P>These fields are available only if you transfer the inventory items to a warehouse at a different fiscal establishment, or if the fiscal establishment is associated with a customer account or a vendor account.</P>



5.  In the lower pane, click **Add** to create a transfer order line. For more information, see [Set up transfer order lines](set-up-transfer-order-lines.md).

6.  On the **Fiscal information** tab, in the **Shipment** field group, specify values in the following fields:
    
    1.  In the **CFOP** field, select the Código Fiscal de Operações e Prestações (CFOP) code for the shipment fiscal document.
    
    2.  In the **Price** field, specify the shipment price for the item.
    
    3.  In the **Sales tax group** field, select a sales tax group for the shipment fiscal document.
    
    4.  In the **Item sales tax group** field, select an item sales tax group for the shipment fiscal document.

7.  In the **Receipt** field group, specify values in the following fields:
    
    1.  In the **CFOP** field, select the CFOP code for the receipt fiscal document.
    
    2.  In the **Price** field, specify the receipt price for the item.
    
    3.  In the **Sales tax group** field, select a sales tax group for the receipt fiscal document.
    
    4.  In the **Item sales tax group** field, select an item sales tax group for the receipt fiscal document.
    

    > [!NOTE]
    > <P>These fields are available only if you transfer the inventory items to a warehouse at a different fiscal establishment.</P>



8.  Click **Posting** \> **Ship transfer order**, and then in the **Ship transfer order** form, specify values in the following fields:
    
    1.  In the **Update** field, select **All** to ship the remaining quantity of items for each line. For more information, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).
    
    2.  Select the **Edit lines** check box to update the transfer order lines based on the option that you selected in the **Update** field.
    
    3.  Select the **Print transfer shipment** check box to print the outbound transfer fiscal document.

9.  Click **OK** to ship the transfer order and generate an outbound transfer fiscal document. The status of the transfer order is updated to **Shipped** in the **Transfer status** field in the **Transfer orders** form.

You can click **Inquiries** \> **Transfer order history** in the **Transfer orders** form to view the history of a transfer order that was shipped.

## See also

[(BRA) Receive an inbound transfer fiscal document](bra-receive-an-inbound-transfer-fiscal-document.md)

[(BRA) Return a transfer fiscal document](bra-return-a-transfer-fiscal-document.md)

[(BRA) Cancel a transfer fiscal document](bra-cancel-a-transfer-fiscal-document.md)

[(BRA) Transfer orders (modified form)](https://technet.microsoft.com/library/jj910973\(v=ax.60\))

[(BRA) Set up the CFOP codes](bra-set-up-the-cfop-codes.md)

[(BRA) Set up the CFOP codes for transfer fiscal documents](bra-set-up-the-cfop-codes-for-transfer-fiscal-documents.md)

[(BRA) Set up the CFOP matrix](bra-set-up-the-cfop-matrix.md)

  


