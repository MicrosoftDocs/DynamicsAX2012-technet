---
title: (BRA) Create and post a purchase complementary fiscal document
TOCTitle: (BRA) Create and post a purchase complementary fiscal document
ms:assetid: 1ea0b2b9-3f16-4ce7-b06f-372082d42c23
ms:mtpsurl: https://technet.microsoft.com/library/JJ710430(v=AX.60)
ms:contentKeyID: 49384322
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- invoices
- BRA
- Brazil
- complementary invoices
- create complementary invoices
- purchase complementary invoices
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a purchase complementary fiscal document 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a purchase complementary fiscal document to adjust a purchase fiscal document that was generated for an incorrect price, Imposto Sobre Produtos Industrializados (IPI), or Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) amount. For more information, see [(BRA) About purchase complementary fiscal documents](bra-about-purchase-complementary-fiscal-documents.md).

You cannot add lines to or delete lines from a purchase complementary fiscal document. You can specify the price or tax adjustment for a specific line. When you post the purchase complementary fiscal document, the adjustment is posted to the fiscal document.

Use the following procedure to create and post a purchase complementary fiscal document.

1.  Click **Accounts payable** \> **Common** \> **Fiscal documents** \> **All purchase complementary fiscal documents**.

2.  On the **Action Pane**, click **Complementary fiscal document** to open the **Fiscal documents** form.

3.  In the **Complementary fiscal document type** field, select the type of complementary fiscal document from the following options:
    
      - **Price** – To create a price complementary fiscal document that is created to adjust an incorrect price for a fiscal document.
    
      - **Tax** – To create an IPI or ICMS complementary fiscal document that is created to adjust an incorrect IPI or ICMS amount for a fiscal document.

4.  Select the fiscal document for which to create a purchase complementary fiscal document, and then click **OK** to open the **Purchase complementary fiscal document** form. All information, except for charges, is updated from the original purchase fiscal document.

5.  Click the **Complementary invoice header** FastTab, and then in the **Document model** field, select the fiscal document model for the purchase complementary fiscal document.

6.  In the **Access key** field, enter the access key for the electronic fiscal document (NF-e).
    

    > [!NOTE]
    > <P>This field is available only if you select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is selected for the document model in the <STRONG>Document model</STRONG> form.</P>



7.  In the **Number** and **Series** fields, enter the invoice number and fiscal document series for the purchase complementary fiscal document.
    

    > [!NOTE]
    > <P>These fields are available only if you select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is not selected for the document model in the <STRONG>Document model</STRONG> form.</P>



8.  In the **Specie** field, select the specie of the fiscal document.

9.  In the **Corrected line amount** field, in the **Invoice lines** area, specify the corrected line amount in the transaction currency. The difference between the amounts in the **Corrected line amount** and **Original line amount** fields is updated in the **Net amount** field.
    
    –or–
    
    In the **Net amount** field, in the **Invoice lines** area, specify the amount to be adjusted in the purchase complementary fiscal document. The corrected line amount is updated in the **Corrected line amount** field.
    

    > [!NOTE]
    > <P>The <STRONG>Corrected line amount</STRONG> and <STRONG>Net amount</STRONG> fields are available only if <STRONG>Price</STRONG> is selected in the <STRONG>Complementary fiscal document type</STRONG> field.</P>



10. In the **Additional IPI amount** and **Additional ICMS amount** fields, in the **Invoice lines** area, specify the IPI and ICMS amounts to be adjusted in the purchase complementary fiscal document.
    

    > [!NOTE]
    > <P>The <STRONG>Additional IPI amount</STRONG> and <STRONG>Additional ICMS amount</STRONG> fields are available only if <STRONG>Tax</STRONG> is selected in the <STRONG>Complementary fiscal document type</STRONG> field.</P>



11. Click the **Line details** FastTab, and then click the **Setup** tab.

12. In the **Item sales tax group** and **Sales tax group** fields, select the item sales tax group and sales tax group for the purchase complementary fiscal document. The tax groups must include ICMS tax codes to create an ICMS complementary fiscal document, or IPI tax codes to create an IPI complementary fiscal document.

13. On the **Action Pane**, click **Post** to post the purchase complementary fiscal document.

## See also

[(BRA) All purchase complementary fiscal documents (list page)](https://technet.microsoft.com/library/jj710524\(v=ax.60\))

[(BRA) Purchase complementary fiscal document (form)](https://technet.microsoft.com/library/jj710577\(v=ax.60\))

  


