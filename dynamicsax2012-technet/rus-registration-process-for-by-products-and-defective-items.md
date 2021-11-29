---
title: (RUS) Registration process for by-products and defective items
TOCTitle: (RUS) Registration process for by-products and defective items
ms:assetid: 38c9fd8f-7817-41c5-8713-7235e6bdd7fe
ms:mtpsurl: https://technet.microsoft.com/library/JJ665289(v=AX.60)
ms:contentKeyID: 49387378
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Registration process for by-products and defective items 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The registration process for by-products and defective items includes the following components:

  - **By-product** – A product that is produced during the manufacturing of the main product.

  - **Defective product**– A product that does not adhere to established standards of quality.

  - **Scrap** – Scrap is a subtype of defective product or by-product.

By-products are further classified into types of by-products, based on their characteristics. These items are separate from the main product and are not defined in the BOM that is specific to the production order. Using the by-product journal, you register the by-products that are created during production.

When defective products are produced, you can register them in the error field of the route card, and report them as finished journal lines. Defective products that do not pass through the production cycle can be returned to the warehouse, using the by-product journal, for rework. When the by-product journal is posted, inventory transactions are changed to a physical status such as **Defective** or **Received**.

When you end a production order, the defective quantity that is registered using the route cards and report as finished journals is compared to the quantity that is registered using by-product journals. If a mismatch occurs, the production order update is canceled.

You can write off scrap from inventory as an inventory loss after receiving it from production using the by-product journal.

The by-product journal allows a negative quantity for the defective or returned production order. You can print the by-product journal using the print option.

The costs of by-products and defective products are calculated when the cost of the production order is calculated. For more information, see [(RUS) Calculate the cost of WIP and finished goods](rus-calculate-the-cost-of-wip-and-finished-goods.md).

  


