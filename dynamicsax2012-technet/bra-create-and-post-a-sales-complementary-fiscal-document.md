---
title: (BRA) Create and post a sales complementary fiscal document
TOCTitle: (BRA) Create and post a sales complementary fiscal document
ms:assetid: 555f5e54-127c-49d9-b1dc-46ef6c956ece
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710509(v=AX.60)
ms:contentKeyID: 49384400
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales invoices
- BRA
- Brazil
- complementary invoices
- Create complementary invoices
- sales complementary invoices
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a sales complementary fiscal document 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a sales complementary fiscal document to adjust a sales fiscal document that was generated for an incorrect price, Imposto Sobre Produtos Industrializados (IPI), or Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) amount. For more information, see [(BRA) About sales complementary fiscal documents](bra-about-sales-complementary-fiscal-documents.md).

You cannot add lines to or delete lines from a sales complementary fiscal document. You can specify the price or tax adjustment for a specific line. When you post the sales complementary fiscal document, the adjustment is posted to the fiscal document.

Use the following procedure to create and post a sales complementary fiscal document.

1.  Click **Accounts receivable** \> **Common** \> **Fiscal documents** \> **All sales complementary fiscal documents**.

2.  On the **Action Pane**, click **Complementary fiscal document** to open the **Fiscal documents** form.

3.  In the **Complementary fiscal document type** field, select the type of complementary fiscal document from the following options:
    
      - **Price** – To create a price complementary fiscal document that is created to adjust an incorrect price for a fiscal document.
    
      - **Tax** – To create an IPI or ICMS complementary fiscal document that is created to adjust an incorrect IPI or ICMS amount for a fiscal document.

4.  Select the fiscal document for which to create a sales complementary fiscal document, and then click **OK** to open the **Sales complementary fiscal document** form. All information, except for charges, is updated from the original sales fiscal document.

5.  Click the **Complementary invoice header** FastTab, and then in the **Invoice date** field, select the date when the sales complementary fiscal document is posted.

6.  In the **Corrected line amount** field, in the **Invoice lines** area, specify the corrected line amount in the transaction currency. The difference between the amounts in the **Corrected line amount** and **Original line amount** fields is updated in the **Amount** field.
    
    –or–
    
    In the **Amount** field, in the **Invoice lines** area, specify the amount to be adjusted in the sales complementary fiscal document. The corrected line amount is updated in the **Corrected line amount** field.
    

    > [!NOTE]
    > <P>The <STRONG>Corrected line amount</STRONG> and <STRONG>Amount</STRONG> fields are available only if <STRONG>Price</STRONG> is selected in the <STRONG>Complementary fiscal document type</STRONG> field.</P>



7.  In the **Additional IPI amount** and **Additional ICMS amount** fields, in the **Invoice lines** area, specify the IPI and ICMS amounts to be adjusted in the sales complementary fiscal document.
    

    > [!NOTE]
    > <P>The <STRONG>Additional IPI amount</STRONG> and <STRONG>Additional ICMS amount</STRONG> fields are available only if <STRONG>Tax</STRONG> is selected in the <STRONG>Complementary fiscal document type</STRONG> field.</P>



8.  Click the **Line details** FastTab, and then click the **Setup** tab.

9.  In the **Sales tax group** and **Item sales tax group** fields, select the sales tax group and item sales tax group for the sales complementary fiscal document. The tax groups must include ICMS tax codes to create an ICMS complementary fiscal document, or IPI tax codes to create an IPI complementary fiscal document.

10. On the **Action Pane**, click **Post** to post the sales complementary fiscal document.

## See also

[(BRA) Sales complementary fiscal document (form)](https://technet.microsoft.com/en-us/library/jj710523\(v=ax.60\))

[(BRA) All sales complementary fiscal documents (list page)](https://technet.microsoft.com/en-us/library/jj710595\(v=ax.60\))

  


