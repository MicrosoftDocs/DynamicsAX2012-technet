---
title: (BRA) Create and post a free text invoice
TOCTitle: (BRA) Create and post a free text invoice
ms:assetid: 7cdc36b6-a962-42ba-9279-843b29218779
ms:mtpsurl: https://technet.microsoft.com/library/JJ710539(v=AX.60)
ms:contentKeyID: 49384430
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- free text invoices
- Brazil
- (BRA)
- Create free text invoice
- post free text invoice
- BR - 00016
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a free text invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a free text invoice by specifying the fiscal document type, operation type, and Código Fiscal de Operações e Prestações (CFOP) code.

## Create a free text invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, on the **Invoice** tab, click **Free text invoice** to create a free text invoice. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

3.  In the **Free text invoice** form, on the **Action Pane**, on the **Invoice** tab, click **Header view**.

4.  In the **Fiscal establishment ID** field, select the identification code for the fiscal establishment.

5.  Click the **Fiscal information** FastTab, and then in the **Fiscal document type** and **Operation type** fields, select the type of fiscal document and type of operation for the transaction. The operation type determines whether the customer invoice affects inventory, ledger, customer, and remittance transactions.

6.  Select the **Final user** check box if the customer is the final user. If this check box is selected, the Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) tax base includes the Imposto Sobre Produtos Industrializados (IPI) tax and any freight charges.

7.  Select the **Service code on delivery address** check box to use service codes based on the delivery address on orders.

8.  On the **Action Pane**, on the **Invoice** tab, click **Line view**, and then click the **Line details** FastTab.

9.  Click the **Fiscal information invoice line** tab, and then in the **CFOP** field, select the CFOP code for the selected free text invoice line. You can view a list of CFOP codes, based on the order type, operation type, location of the fiscal establishment, and location of the customer.

10. Select the **Service invoice** check box to generate a service invoice, and then in the **Service code** field, select the fiscal classification applied for services.
    

    > [!NOTE]
    > <P>The <STRONG>Service code</STRONG> field is available only if you select the <STRONG>Service invoice</STRONG> check box.</P>



11. On the **Action Pane**, on the **Invoice** tab, click **Fiscal document texts** to open the **Fiscal document text** form, where you can attach fiscal document texts to the invoice. For more information, see[(BRA) Attach fiscal document texts to a free text invoice](bra-attach-fiscal-document-texts-to-a-free-text-invoice.md)

## Post and print a free text invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select the free text invoice to post.

3.  On the **Action Pane**, on the **Invoice** tab, click **Post** to open the **Post free text invoice** form.

4.  Click the **Bill of lading** tab, and then in the **Volume type** and **Volume quantity** fields, enter the volume type and volume quantity that are used in an invoice posting.
    

    > [!NOTE]
    > <P>The <STRONG>Bill of lading</STRONG> tab is available only if the <STRONG>Service invoice</STRONG> check box is not selected on the <STRONG>Fiscal information invoice line</STRONG> tab on the <STRONG>Line details</STRONG> FastTab in the <STRONG>Free text invoice</STRONG> form.</P>



5.  Click **OK** to post the free text invoice.

## See also

[Free text invoice (form)](https://technet.microsoft.com/library/aa556897\(v=ax.60\))

  


