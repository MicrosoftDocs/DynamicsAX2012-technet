---
title: (BRA) About purchase posting enhancements
TOCTitle: (BRA) About purchase posting enhancements
ms:assetid: 2e6c8ac5-b40b-40d0-a280-1fa5de8fee34
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710456(v=AX.60)
ms:contentKeyID: 49384347
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Brazil
- (BRA)
- purchase posting
- purchase posting enhancements
- BR - 00026
audience: Application User
ms.search.region: Brazil
---

# (BRA) About purchase posting enhancements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The following enhancements have been made for purchase posting:

  - You can create and post a purchase order or a return purchase order by specifying the operation type and the Código Fiscal de Operações e Prestações (CFOP) code. You must specify CFOP codes for a purchase order, a returned item, or a product that has an **Item** type.

  - You can change the delivery address for a return purchase order. The **CNPJ/CPF** and **IE** fields in the **Purchase order** form are updated based on the delivery address that is specified for the vendor in the **Vendors** form. You can also modify the delivery address for the vendor in the **Create purchase order** form or in the purchase order lines.

  - You can attach a fiscal document text to a purchase order or vendor invoice.

  - You can create reference invoices that link one or more vendor invoice references when an invoice is created.

  - You can generate, post, and print the vendor invoice for a nontaxpayer vendor.

  - You can cancel an incorrect purchase order and generate a negative purchase order. When you post a negative purchase order and run the fiscal book integration process, all ledger and financial transactions that are related to the purchase order are reversed in the fiscal books.

## See also

[(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md)

[(BRA) Cancel a vendor fiscal document](bra-cancel-a-vendor-fiscal-document.md)

  


