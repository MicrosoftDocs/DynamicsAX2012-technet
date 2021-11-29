---
title: Use bar codes in warehouse operations
TOCTitle: Use bar codes in warehouse operations
ms:assetid: adbc48d2-6d6b-4ad1-8051-16fcbad113be
ms:mtpsurl: https://technet.microsoft.com/library/Dn906144(v=AX.60)
ms:contentKeyID: 63972493
author: Khairunj
ms.date: 05/06/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Use bar codes in warehouse operations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]



> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes features that are available only if you are running Microsoft Dynamics AX 2012 R3 Cumulative Update 8. Bar code lookup functionality can be used with products and product variants to support several inbound operations that are carried out by warehouse workers on mobile devices. The inbound operations supported by bar code lookup are:

  - Purchase order receiving

  - Transfer order receiving

  - Load receiving

The following operations are not supported:

  - Guided cycle counting

  - Cluster picking

  - Production scrap

  - Return order receiving

## Configure bar codes for products

To configure bar codes for a specific product or product variant:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Warehouse** tab, click the **Bar codes** button. This opens the **Bar code** form.

3.  Select the **Scanning** check box for the products or variants for which you want to use bar code scanning. When this field is selected, the system ensures that bar codes that are scanned are unique across all bar codes within the legal entity.

After you have configured bar codes for products or variants, you can use them in warehousing scenarios, such as receiving purchase orders and transfer orders via a mobile device. For example, if you create a purchase order with a product variant line, the warehouse worker who receives the purchase order can scan or enter the bar code into the **Item** field on the **PO receipt** form on their mobile device. After you do this, the product dimensions for the product variant are automatically populated. If the bar code that is scanned does not correspond to an item on the purchase order, an error is displayed.

## See also

[About product variants](about-product-variants.md)

[Setting up mobile devices](setting-up-mobile-devices.md)

  


