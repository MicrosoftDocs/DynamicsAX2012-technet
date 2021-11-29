---
title: (BRA) Setting up standard text in accounting transactions
TOCTitle: (BRA) Setting up standard text in accounting transactions
ms:assetid: 949b0824-4f46-4b11-b280-d325cff4e7a9
ms:mtpsurl: https://technet.microsoft.com/library/JJ710571(v=AX.60)
ms:contentKeyID: 49384461
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- accounting transactions
- set up standard text
- standard text
audience: Application User
ms.search.region: Brazil
---

# (BRA) Setting up standard text in accounting transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

All Brazilian accounting transactions must contain text that clearly states transaction details. The text can contain information such as the invoice number, date, and customer number or vendor number.

You can use defined variables in the text. The variables are replaced with the corresponding values when the transaction is posted. Use the following variables to set up text for the transactions:

  - %1 – Payment date

  - %2 – Invoice number

  - %3 – Voucher number

  - %4 – Vendor account number

  - %5 – Withholding tax type

  - %6 – Consolidated account number

  - %7 – Vendor or customer name

In vendor invoice transactions, the %7 variable is replaced with the vendor name, and in sales invoice transactions, it is replaced with the customer name.

## See also

[(BRA) Set up a default description for withholding tax, interest, and fine payments](bra-set-up-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

[(BRA) Set up a default description for a consolidated legal entity](bra-set-up-a-default-description-for-a-consolidated-legal-entity.md)

  


