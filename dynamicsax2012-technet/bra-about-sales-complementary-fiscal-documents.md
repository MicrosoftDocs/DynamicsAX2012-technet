---
title: (BRA) About sales complementary fiscal documents
TOCTitle: (BRA) About sales complementary fiscal documents
ms:assetid: a4b50672-3a96-4eaa-9394-29e17ff43345
ms:mtpsurl: https://technet.microsoft.com/library/JJ710586(v=AX.60)
ms:contentKeyID: 49384472
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- complementary invoices
- about complementary invoices
- sales complementary invoices
audience: Application User
ms.search.region: Brazil
---

# (BRA) About sales complementary fiscal documents 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must create a sales complementary fiscal document to adjust a sales fiscal document that was generated for an incorrect price, Imposto Sobre Produtos Industrializados (IPI), or Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) amount. A sales complementary fiscal document is issued only to adjust a positive difference. For example, a sales complementary fiscal document is generated if the price of an item on the original customer fiscal document is incorrect, and the correct price for the item is higher than the price recorded on the original customer fiscal document.

You can create a sales complementary fiscal document to adjust an error in the price or quantity of items or services, the tax percentage, or the tax calculation.

The sales complementary fiscal document is a sales fiscal document that complements the original sales fiscal document. All information, except for charges, is updated from the original sales fiscal document. You cannot add lines to or delete lines from a sales complementary fiscal document.

The following types of sales complementary fiscal documents are available:

  - Price complementary fiscal document – A complementary fiscal document that is created to adjust an incorrect price for a fiscal document. The correct price must be higher than the price recorded on the original fiscal document. The price difference is charged to the customer.

  - IPI complementary fiscal document – A complementary fiscal document that is created to adjust an incorrect IPI tax amount for a fiscal document. The IPI tax difference is charged to the customer.

  - ICMS complementary fiscal document – A complementary fiscal document that is created to adjust an incorrect ICMS tax amount for a fiscal document. The ICMS tax difference is received by the legal entity and paid to the tax authorities.

The tax groups that you select for the sales complementary fiscal document must include ICMS tax codes to create an ICMS complementary fiscal document, or IPI tax codes to create an IPI complementary fiscal document. For example, if you are creating an IPI complementary fiscal document and the existing tax groups do not have the IPI tax type, you must select a tax group that has an IPI tax code.

## See also

[(BRA) Create and post a sales complementary fiscal document](bra-create-and-post-a-sales-complementary-fiscal-document.md)

  


