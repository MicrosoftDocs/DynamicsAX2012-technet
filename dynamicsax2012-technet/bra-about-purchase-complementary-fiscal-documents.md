---
title: (BRA) About purchase complementary fiscal documents
TOCTitle: (BRA) About purchase complementary fiscal documents
ms:assetid: 3d439f7e-9240-4521-a873-4ce029e1a67f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710465(v=AX.60)
ms:contentKeyID: 49384356
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- purchase complementary invoices
- about complementary invoices
- Complementary invoices
- BR - 00004
---

# (BRA) About purchase complementary fiscal documents 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must create a purchase complementary fiscal document to adjust a purchase fiscal document that was generated for an incorrect price, Imposto Sobre Produtos Industrializados (IPI), or Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) amount. A purchase complementary fiscal document is issued only to adjust a positive difference. For example, a purchase complementary fiscal document is generated if the price of an item on the original purchase fiscal document is incorrect, and the correct price for the item is higher than the price recorded on the original purchase fiscal document.

You can create a purchase complementary fiscal document to adjust an error in the price or quantity of items or services, the tax percentage, or the tax calculation.

The purchase complementary fiscal document is a purchase fiscal document that complements the original purchase fiscal document. All information, except for charges, is updated from the original purchase fiscal document. You cannot add lines to or delete lines from a purchase complementary fiscal document.

The following types of purchase complementary fiscal documents are available:

  - Price complementary fiscal document – A complementary fiscal document that is created to adjust an incorrect price for a fiscal document. The correct price must be higher than the price recorded on the original fiscal document. The price difference is charged to the vendor.

  - IPI complementary fiscal document – A complementary fiscal document that is created to adjust an incorrect IPI tax amount for a fiscal document. The IPI tax difference is charged to the vendor.

  - ICMS complementary fiscal document – A complementary fiscal document that is created to adjust an incorrect ICMS tax amount for a fiscal document. The ICMS tax difference is received by the legal entity and paid to the tax authorities.

The tax groups that you select for the purchase complementary fiscal document must include ICMS tax codes to create an ICMS complementary fiscal document, or IPI tax codes to create an IPI complementary fiscal document. For example, if you are creating an IPI complementary fiscal document and the existing tax groups do not have the IPI tax type, you must select a tax group that has an IPI tax code.

## See also

[(BRA) Create and post a purchase complementary fiscal document](bra-create-and-post-a-purchase-complementary-fiscal-document.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

