---
title: About approved vendors
TOCTitle: About approved vendors
ms:assetid: f12d22ca-eadc-45a2-920a-623b5d992aef
ms:mtpsurl: https://technet.microsoft.com/library/Hh227508(v=AX.60)
ms:contentKeyID: 36059929
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About approved vendors 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You may often purchase materials and services from certain vendors on a recurring basis. For example, if you use a particular product in several of your formulas, you may purchase the product weekly from one or more preferred vendors. To speed up transactions that include this product, you can authorize one or more vendors to supply the product by setting them up as approved vendors.

## Authorizing approved vendors

To authorize an approved vendor to supply a product, you use the **Approved vendor list** form. You can access this form from the **Released products** list page or from the **Released product details** form in **Product information management**.

When you add an approved vendor for a product, you set an effective approval period. This period identifies when approval starts and ends for the product. The effective start date can be any date. However, the expiration date must be the current date or a later date.

## Validating approved vendors

When you submit a transaction for a product that uses an approved vendor, a validation is performed against the **Approved vendor list**. This is to validate that the vendor appears on the list and that the transaction falls in the effective approval period. If the product has one or more approved vendors and the vendor you select is not one of them, the **Approved vendor check** method determines whether you can continue with the transaction. The types of transactions that are validated for approved vendors are as follows:

  - Purchase agreement setup with data entry enabled up to the Confirmation process

  - Purchase orders at both data entry and journalizing

  - Planned purchase orders

  - Production orders

  - Batch orders

  - Purchase orders created from sales orders at both data entry and journalizing

## Setting check method for the approved vendor

When you approve a product for a vendor, you specify a check method for an approved vendor. This method determines the action taken if you select a vendor that is not listed in the product’s **Approved vendor list**, or if the transaction date falls outside the effective approval period. The check methods include the following:

  - **No check** – No validation is performed. Therefore, any vendor that you select is allowed.

  - **Warning only** – A warning message is displayed, but you can continue with the transaction. This action is the default method.

  - **Not allowed** – An error message is displayed, and you must select an approved vendor to continue with the transaction.

## See also

[Approved vendor list (form)](https://technet.microsoft.com/library/hh328745\(v=ax.60\))

[(PM) Released product details (form)](https://technet.microsoft.com/library/hh352306\(v=ax.60\))

  


