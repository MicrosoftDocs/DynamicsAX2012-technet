---
title: Specifying overdelivery or underdelivery on transfer order lines
TOCTitle: Specifying overdelivery or underdelivery on transfer order lines
ms:assetid: 4b4dbe39-5db1-413e-9bc1-e6c0ac59b191
ms:mtpsurl: https://technet.microsoft.com/library/Hh352200(v=AX.60)
ms:contentKeyID: 36687834
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Specifying overdelivery or underdelivery on transfer order lines 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you update a picking list registration, the item quantity must match the quantity that is registered in the **Transfer quantity** field on the transfer order line. To deliver a quantity that differs from the quantity given on the transfer order line, you must enable a percentage of overdelivery or underdelivery for the product. The overdelivery and underdelivery settings can be enabled directly on the product or they can be enabled for individual transfer order lines:

## Enable overdeliver and underdelivery

The overdelivery and underdelivery percentage can be enabled directly on the product or it can be enabled for individual transfer order lines:

  - Enabled on the product – Click **Product information management** \> **Common** \> **Released products**. Select a product and then click **Edit** on the **Action Pane**. Then, on the **Sell** FastTab, enter a percentage in the **Overdelivery** and **Underdelivery** fields. The percentages of overdelivery and underdelivery that are specified are inherited by the transfer order line.

  - Enabled directly on the transfer order line – The overdelivery or underdelivery percentages can be set directly on the transfer order line or the percentages that are inherited from the product can be changed.


> [!NOTE]
> <P>To use overdelivery and underdelivery percentages for transfer orders, the <STRONG>Accept overdelivery</STRONG> and <STRONG>Accept underdelivery</STRONG> check boxes must be selected in the <STRONG>Inventory and warehouse management parameters</STRONG> form. Click <STRONG>Inventory management</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Inventory and warehouse management parameters</STRONG>. Click the <STRONG>Transport</STRONG> link, and select the <STRONG>Accept overdelivery</STRONG> and <STRONG>Accept underdelivery</STRONG> check boxes.</P>



### Specify overdelivery or underdelivery on a transfer order line

1.  Follow the steps to create a transfer order line and, in the **Transfer orders** form, click the **Setup** tab in the lower pane of the form.

2.  In the **Overdelivery** or the **Underdelivery** fields, enter a percentage.

3.  Process the transfer order line.
    

    > [!TIP]
    > <P>An overdelivery percentage for the transfer order line is validated during the pick registration and the shipment update.</P>



## See also

[Set up transfer order lines](set-up-transfer-order-lines.md)

  


