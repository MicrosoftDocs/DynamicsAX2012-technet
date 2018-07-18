---
title: (BRA) Cancel a sales complementary fiscal document
TOCTitle: (BRA) Cancel a sales complementary fiscal document
ms:assetid: 5fa173b2-e5ca-4509-bd8e-557181f8e7e4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710517(v=AX.60)
ms:contentKeyID: 49384408
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Cancel
- BRA
- Brazil
- complementary invoices
- Cancel complementary invoice
- cancel invoices
- Forms.SalesComplementaryInvoiceListPage
- BR-00044
- MsDynAx060.Forms.SalesComplementaryInvoiceListPage
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel a sales complementary fiscal document 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel an incorrect sales complementary fiscal document and provide a reason for the cancellation. When you cancel a sales complementary fiscal document, a sales complementary fiscal document is created with a negative price amount, an Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) amount, or an Imposto Sobre Produtos Industrializados (IPI) amount. When you post the negative sales complementary fiscal document, the original complementary fiscal document is marked as canceled, and all of the ledger transactions and financial transactions are reversed. The original sales complementary fiscal document is reported in the fiscal books as canceled, and the negative sales complementary fiscal document is not reported in the fiscal books.


> [!NOTE]
> <P>The procedure for completing this task changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## Cancel a sales complementary fiscal document

1.  Click **Accounts receivable** \> **Common** \> **Fiscal documents** \> **All sales complementary fiscal documents**.

2.  Select the sales complementary fiscal document to cancel.

3.  On the **Action Pane**, click **Cancel fiscal document**. A negative sales complementary fiscal document is created in the **Sales complementary fiscal document** form.

4.  On the **Action Pane**, click **Post** to post the negative sales complementary fiscal document. When you post the negative sales complementary fiscal document, the original sales complementary fiscal document is marked as canceled.

## (BRA) Cancel a sales complementary fiscal document in cumulative update 6 for Microsoft Dynamics AX 2012 R2

1.  Click **Accounts receivable** \> **Common** \> **Fiscal documents** \> **All sales complementary fiscal documents**.

2.  Select the sales complementary fiscal document to cancel.

3.  On the **Action Pane**, click **Cancel fiscal document**.

4.  In the **Cancel fiscal document** dialog box, in the **Reason code** field, select the identification code for the reason to cancel the sales complementary fiscal document.

5.  In the **Reason comment** field, enter or update the reason to cancel the sales complementary fiscal document.
    

    > [!NOTE]
    > <P>The reason for the cancellation must contain a minimum of 15 characters.</P>



6.  Click **Create corrected invoice** to create a negative sales complementary fiscal document in the **Sales complementary fiscal document** form.

7.  On the **Action Pane**, click **Post** to post the negative sales complementary fiscal document. When you post the negative sales complementary fiscal document, the original sales complementary fiscal document is marked as canceled.

## See also

[(BRA) About sales complementary fiscal documents](bra-about-sales-complementary-fiscal-documents.md)

[(BRA) All sales complementary fiscal documents (list page)](https://technet.microsoft.com/en-us/library/jj710595\(v=ax.60\))

[(BRA) Sales complementary fiscal document (form)](https://technet.microsoft.com/en-us/library/jj710523\(v=ax.60\))

  


