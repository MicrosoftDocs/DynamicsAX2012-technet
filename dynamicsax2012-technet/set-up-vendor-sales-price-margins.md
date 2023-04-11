---
title: Set up vendor sales price margins
TOCTitle: Set up vendor sales price margins
ms:assetid: bc92aa6b-8b56-4a47-91b8-a6a67355a6ac
ms:mtpsurl: https://technet.microsoft.com/library/Hh597224(v=AX.60)
ms:contentKeyID: 39519295
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up vendor sales price margins 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

The vendor sales price margin contains a formula that converts the vendor's suggested retail price or the vendor's purchase price for a product to a sales price in local currency. The sales price margin is used only if there is no entry for the product in the vendor's sales price points.


> [!NOTE]
> <P>If no suggested retail price is imported for a retail vendor's product, the sales price can be calculated based on the purchase price. Retail uses the <STRONG>Vendor sales price margin setup</STRONG> form to calculate the sales price.</P>



1.  Click **Retail** \> **Setup** \> **Product/order creation** \> **Vendor sales price margin setup**.

2.  In the **Vendor sales price margin setup** form, select the vendor to set up a sales price margin for.

3.  If the vendor suggested that a specific factor be used to calculate the sales price of a product, enter the suggested factor in the **Suggested contribution ratio** field. Otherwise, enter a factor in the **Contribution ratio** field.

## See also

[Import vendor products overview](import-vendor-products-overview.md)

[Vendor sales price margin setup (form)](https://technet.microsoft.com/library/hh580650\(v=ax.60\))

  


