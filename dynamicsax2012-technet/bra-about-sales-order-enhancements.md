---
title: (BRA) About sales order enhancements
TOCTitle: (BRA) About sales order enhancements
ms:assetid: d6adad62-6e64-4c6e-b02c-baf92c44d15b
ms:mtpsurl: https://technet.microsoft.com/library/JJ663946(v=AX.60)
ms:contentKeyID: 49384535
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- sales posting
- sales posting enhancements
- BR - 00029
audience: Application User
ms.search.region: Brazil
---

# (BRA) About sales order enhancements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The following enhancements have been made to sales orders in Brazil:

  - You can create and post a sales order by specifying the fiscal document type and the Código Fiscal de Operações e Prestações (CFOP) code. You can also summarize the sales orders before posting.

  - You can change the delivery address for a sales order. The **CNPJ/CPF** and **IE** fields in the **Sales order** form are updated with the Cadastro Nacional da Pessoa Jurídica (CNPJ)/Cadastro de Pessoas Físicas (CPF) and Inscrição Estadual (IE) of the customer, based on the address that is selected as the delivery address for the customer in the **Customers** form. If the CNPJ/CPF and IE are not specified for the address, the **CNPJ/CPF** and **IE** fields in the **Sales order** form are updated with the CNPJ/CPF and IE on the **Fiscal information** FastTab in the **Customers** form. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md)

  - You can cancel an incorrect fiscal document. When you cancel a fiscal document, the fiscal document is marked as canceled, and all the ledger and financial transactions are reversed. For more information, see [(BRA) Cancel a customer fiscal document](bra-cancel-a-customer-fiscal-document.md).

  - You can create delivery schedules for sales orders. The CFOP codes and tax information on the delivery lines are copied from the original sales line. For more information, see [(BRA) Create sales delivery schedules](bra-create-sales-delivery-schedules.md).

  


