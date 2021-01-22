---
title: (BRA) Cancel a customer NF-e
TOCTitle: (BRA) Cancel a customer NF-e
ms:assetid: 20338892-f57f-437f-baca-f45e202c1b93
ms:mtpsurl: https://technet.microsoft.com/library/JJ933498(v=AX.60)
ms:contentKeyID: 50935112
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- Cancel customer NF-e
- cancel electronic fiscal document
- Customer electronic fiscal document
- Cancel NF-e
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel a customer NF-e 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel a customer nota fiscal eletrônica (NF-e) that is incorrect. You can cancel a customer NF-e before you submit it to the Secretaria da Fazenda (SEFAZ) or after it is processed or approved by SEFAZ.


> [!NOTE]
> <P>You can cancel a processed or approved customer NF-e. You can cancel an approved NF-e only if SEFAZ approves the cancellation.</P>



When you cancel a customer NF-e, the original NF-e is marked as canceled, and all of the ledger and financial transactions are reversed.

## Cancel a customer NF-e that is generated from a sales order

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select the sales order that is associated with the original NF-e.

3.  On the **Action Pane**, on the **Sell** tab, click **Cancel fiscal document** to cancel the sales order. For more information, see [(BRA) Cancel a customer fiscal document](bra-cancel-a-customer-fiscal-document.md).

## Cancel a customer NF-e that is generated from a free text invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select the free text invoice that is associated with the original NF-e.

3.  On the **Action Pane**, click **Cancel fiscal document** to cancel the free text invoice. For more information, see [(BRA) Cancel a free text invoice](bra-cancel-a-free-text-invoice.md).

## Cancel a customer NF-e that is generated from a sales complementary fiscal document

1.  Click **Accounts receivable** \> **Common** \> **Fiscal documents** \> **All sales complementary fiscal documents**.

2.  Select the sales complementary fiscal document that is associated with the original NF-e.

3.  On the **Action Pane**, click **Cancel fiscal document** to cancel the sales complementary fiscal document. For more information, see [(BRA) Cancel a sales complementary fiscal document](bra-cancel-a-sales-complementary-fiscal-document.md).

## See also

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/library/jj911252\(v=ax.60\))

[(BRA) Free text invoice (modified form)](https://technet.microsoft.com/library/jj933514\(v=ax.60\))

[(BRA) All sales complementary fiscal documents (list page)](https://technet.microsoft.com/library/jj710595\(v=ax.60\))

[(BRA) Sales complementary fiscal document (form)](https://technet.microsoft.com/library/jj710523\(v=ax.60\))

[(BRA) Cancel customer fiscal document (form)](https://technet.microsoft.com/library/jj933503\(v=ax.60\))

  


