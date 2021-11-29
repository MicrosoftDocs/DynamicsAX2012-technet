---
title: (BRA) Cancel a purchase complementary fiscal document
TOCTitle: (BRA) Cancel a purchase complementary fiscal document
ms:assetid: cdf7db1d-671f-47fb-8f00-f147acb4674e
ms:mtpsurl: https://technet.microsoft.com/library/JJ663924(v=AX.60)
ms:contentKeyID: 49384510
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cancel
- BRA
- Brazil
- complementary invoices
- purchase complementary invoices
- Forms.PurchComplementaryInvoiceListPage
- Cancel complementary invoices
- BR-00044
- MsDynAx060.Forms.PurchComplementaryInvoiceListPage
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel a purchase complementary fiscal document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel an incorrect purchase complementary fiscal document and provide a reason for the cancellation. When you cancel a purchase complementary fiscal document, a purchase complementary fiscal document is created with a negative price amount, an Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) amount, or an Imposto Sobre Produtos Industrializados (IPI) amount. When you post the negative purchase complementary fiscal document, the original complementary fiscal document is marked as canceled, and all of the ledger transactions and financial transactions are reversed. The original purchase complementary fiscal document is reported in the fiscal books as canceled, and the negative purchase complementary fiscal document is not reported in the fiscal books.


> [!NOTE]
> <P>The procedure for completing this task changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## Cancel a purchase complementary fiscal document

1.  Click **Accounts payable** \> **Common** \> **Fiscal documents** \> **All purchase complementary fiscal documents**.

2.  Select the purchase complementary fiscal document to cancel.

3.  On the **Action Pane**, click **Cancel fiscal document**. A negative purchase complementary fiscal document is created in the **Purchase complementary fiscal document** form.

4.  On the **Action Pane**, click **Post** to post the negative purchase complementary fiscal document. When you post the negative purchase complementary fiscal document, the original purchase complementary fiscal document is marked as canceled.

## Cancel a purchase complementary fiscal document in cumulative update 6 for Microsoft Dynamics AX 2012 R2

1.  Click **Accounts payable** \> **Common** \> **Fiscal documents** \> **All purchase complementary fiscal documents**.

2.  Select the purchase complementary fiscal document to cancel.

3.  On the **Action Pane**, click **Cancel fiscal document**.

4.  In the **Cancel fiscal document** form, in the **Reason code** field, select the identification code for the reason to cancel the purchase complementary fiscal document.

5.  In the **Reason comment** field, enter or update the reason to cancel the purchase complementary fiscal document.
    

    > [!NOTE]
    > <P>The reason for the cancellation must contain a minimum of 15 characters.</P>



6.  Click **Create corrected invoice** to create a negative purchase complementary fiscal document in the **Purchase complementary fiscal document** form.

7.  On the **Action Pane**, click **Post** to post the negative purchase complementary fiscal document. When you post the negative purchase complementary fiscal document, the original purchase complementary fiscal document is marked as canceled.

## See also

[(BRA) About purchase complementary fiscal documents](bra-about-purchase-complementary-fiscal-documents.md)

[(BRA) All purchase complementary fiscal documents (list page)](https://technet.microsoft.com/library/jj710524\(v=ax.60\))

[(BRA) Purchase complementary fiscal document (form)](https://technet.microsoft.com/library/jj710577\(v=ax.60\))

  


