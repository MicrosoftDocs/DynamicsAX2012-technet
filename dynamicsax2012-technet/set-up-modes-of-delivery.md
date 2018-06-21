---
title: Set up modes of delivery
TOCTitle: Set up modes of delivery
ms:assetid: f7a4cf07-30f7-4755-b0b8-d9e4ea24b2bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ728719(v=AX.60)
ms:contentKeyID: 49556624
ms.date: 04/29/2014
mtps_version: v=AX.60
---

# Set up modes of delivery [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to specify which modes of delivery are available to customers in your retail stores and online stores. You can also specify different modes of delivery for specific combinations of retail channels, products, and geographic areas.

To set up the modes of delivery that you offer your customers, follow these steps:

1.  Click **Procurement and sourcing** \> **Setup** \> **Distribution** \> **Modes of delivery**.

2.  Click **New** or select an existing mode of delivery, and then, on the **Retail channels** FastTab, click **Add line** to add one or more channels that use the mode of delivery.

3.  In the **Choose organization nodes** form, select an organization hierarchy.

4.  Expand the **Available organization nodes:** list, select an organization node that includes the channels that you want to add, and then click **Add \>\>**.

5.  When you have finished adding channels, click **Close**.

6.  On the **Products** FastTab, specify which products to include or exclude from the mode of delivery. Click **Add line** to add one line, or click **Add products** to add multiple lines.

7.  On each line, in the **Category** and **Product** fields, specify the product. If the product is a variant, select it in the **Product variant** field.

8.  In the **Line type** field, specify whether to include or exclude the product from the mode of delivery.
    
    For example, if all of your products except one use the mode of delivery, add two lines. On the first line, select **ALL** in the **Category** field, and select **Include** in the **Line type** field. On the second line, specify the product to exclude, and then select **Exclude** in the **Line type** field.

9.  On the **Addresses** FastTab, click **Add line** to specify which countries or regions and states or provinces to include or exclude from the mode of delivery.
    
    For example, if the mode of delivery does not serve Alaska or Hawaii, add three lines. On the first line, select **USA** in the **Country/region** field, and then select **Include** in the **Line type** field. On the second line, select **USA** in the **Country/region** field, select **AK** in the **State/province** field, and then select **Exclude** in the **Line type** field. On the third line, do the same to exclude Hawaii.

## See also

[Set up shipping charges for retail stores](set-up-shipping-charges-for-retail-stores.md)

[Set up shipping charges for online stores](set-up-shipping-charges-for-online-stores.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

