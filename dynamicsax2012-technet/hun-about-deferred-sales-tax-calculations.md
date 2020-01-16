---
title: (HUN) About deferred sales tax calculations
TOCTitle: (HUN) About deferred sales tax calculations
ms:assetid: 3a8788c1-3efd-4faf-86b3-8f0999492c43
ms:mtpsurl: https://technet.microsoft.com/library/JJ664263(v=AX.60)
ms:contentKeyID: 49385353
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) About deferred sales tax calculations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Item sales tax groups** form to specify that value-added taxes (VAT) are posted to a deferred VAT account. These VAT amounts are transferred from the deferred VAT account to a regular sales tax account on the due date of the invoice.

You can designate the deferred VAT account in the **Ledger posting groups** form. For more information, see [(HUN) Ledger posting groups (modified form)](https://technet.microsoft.com/library/jj664253\(v=ax.60\)).

Deferred tax postings work for the following document types and journals:

  - Sales orders

  - Free text invoices

  - Purchase orders

  - Invoice journals

  - Invoice registers

  - Invoice approval journals

If a transaction uses a sales tax for which the **Deferred VAT** check box is selected in the **Item sales tax groups** form for at least one of those document types or journals, the following sales tax transactions are created when the transaction is posted.

  - The sales tax amount on the posting date is posted to the deferred tax account that is selected in the **Ledger posting groups** form.

  - The sales tax amount on the date of the VAT register is reversed from the deferred tax account that is selected in the **Ledger posting groups** form.

  - The sales tax amount on the date of the VAT register is posted to the default sales tax payable or sales tax receivable account.

For free text invoices and purchase orders, if the document line amounts are distributed among financial dimensions, the sale tax amounts are distributed just like the document line amounts are distributed.

## See also

[(HUN) Ledger posting groups (modified form)](https://technet.microsoft.com/library/jj664253\(v=ax.60\))

  


