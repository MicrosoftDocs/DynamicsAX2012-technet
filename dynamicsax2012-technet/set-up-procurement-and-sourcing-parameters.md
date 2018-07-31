---
title: Set up procurement and sourcing parameters
TOCTitle: Set up procurement and sourcing parameters
ms:assetid: 1a655389-e7bb-49ac-8c65-5f89474feb48
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208453(v=AX.60)
ms:contentKeyID: 36056119
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameter
- parameters
- procurement
- sourcing
- purchasing
audience: Application User
ms.search.region: Global
---

# Set up procurement and sourcing parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you begin to work in **Procurement and sourcing** in Microsoft Dynamics AX, you set up default values in the **Procurement and sourcing parameters** form. By setting default values, you can automate some of the data entry that is required when documents are created for procurement activities.

Most default values can be overridden at transaction time.

## Set up Procurement and sourcing parameters

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  Click **General** to set up default values that appear when a requester creates a purchase order.

3.  Click **Vendor** to set up the default settings for prospective vendor requests. For more information about vendor requests, see [About vendor request configuration](about-vendor-request-configuration.md).

4.  Click **Updates** to set up parameters for product delivery. This includes rules for accepting deliveries, updating invoices, and product receipts.
    
    Optional: Click the **Update order lines** button to modify parameters that control whether updates to purchase order lines are allowed when you modify the purchase order header.

5.  Click **Prices** to set up options for pricing and discounts on purchase orders. You can select options for calculating and allocating discounts and charges, such as freight, to lines in a purchase order.

6.  Click **Cycles** to select the purchase cycles that are used in the legal entity.
    

    > [!NOTE]
    > <P>(ESP) This control is available only to legal entities whose primary address is in Spain.</P>



7.  Click **AIF** to set up the default journal for imported price and discount agreements.

8.  Click **Inventory dimensions** to specify inventory dimensions that are displayed on purchase order lines.

9.  Click **Request for quotation** to specify default values for requests for quotations, such as purchase type, expiration date, delivery information, payment terms, and trade agreement journal.

10. Click **Procurement site settings** to specify whether users can enter comments and ratings to rate products and vendor performance after a purchase order has been fulfilled.

11. Click **Number sequences** to set up automated identification number assignment for vendors and documents.

## See also

[Set up requests for quotation](set-up-requests-for-quotation.md)

[Procurement and sourcing parameters (form)](https://technet.microsoft.com/en-us/library/hh208706\(v=ax.60\))

  


