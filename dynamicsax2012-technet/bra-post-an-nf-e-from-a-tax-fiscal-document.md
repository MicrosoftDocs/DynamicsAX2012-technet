---
title: (BRA) Post an NF-e from a tax fiscal document
TOCTitle: (BRA) Post an NF-e from a tax fiscal document
ms:assetid: 69cb6c90-7e71-42f4-ac35-da479884502d
ms:mtpsurl: https://technet.microsoft.com/library/JJ937987(v=AX.60)
ms:contentKeyID: 50950776
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- tax fiscal document
- Post electronic fiscal document
- Post NF-e
audience: Application User
ms.search.region: Brazil
---

# (BRA) Post an NF-e from a tax fiscal document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a new tax fiscal document and generate a nota fiscal eletrônica (NF-e). When you post the document, an NF-e XML message is generated and submitted to the Secretaria da Fazenda (SEFAZ).

1.  Click **General ledger** \> **Journals** \> **All tax fiscal documents**.

2.  On the **Action Pane**, click **Tax fiscal document** to open the **Tax fiscal document** form. For more information, see [(BRA) Tax fiscal document (form)](https://technet.microsoft.com/library/jj710428\(v=ax.60\)).

3.  On the **Tax fiscal document header** FastTab, in the **Tax fiscal document type** field, select a type of Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax fiscal document.

4.  In the **Fiscal establishment ID** field, select the identification code of the fiscal establishment that receives or issues the ICMS tax fiscal document.

5.  In the **Account type** field, specify whether the fiscal document is related to a customer or a vendor.
    

    > [!NOTE]
    > <P>The <STRONG>Account type</STRONG> field is available only if you select <STRONG>ICMS tax transfer</STRONG> in the <STRONG>Tax fiscal document type</STRONG> field.</P>



6.  In the **Account number** field, select the customer or vendor account. The **Name** and **Reference** fields are updated with the name and address of the customer or vendor.

7.  In the **Date** field, select the invoice date.

8.  In the **Fiscal document type** field, select the type of the fiscal document for the NF-e. You can select only the fiscal document types that are defined for the fiscal establishment of the site for the selected sales order line.

9.  To create a line for the ICMS tax fiscal document, follow these steps:
    
    1.  In the **Tax fiscal document line** area, in the **Item description** field, enter the description of the item for the ICMS tax fiscal document line.
    
    2.  In the **CFOP** field, select the Código Fiscal de Operações e Prestações (CFOP) code for the ICMS tax fiscal document line. The CFOP codes that are available depend on the fiscal establishment, the direction, and the address of the customer or vendor.
    
    3.  In the **Sales tax code** field, select the sales tax code for the ICMS tax fiscal document line.
    
    4.  In the **Amount** field, specify the tax amount for the ICMS tax fiscal document line.
    
    You can also click **Fiscal document texts** to open the **Fiscal document texts** form, where you can attach fiscal document texts to the ICMS tax fiscal document line. For more information, see [(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md).
    

    > [!NOTE]
    > <P>You can create only one ICMS tax fiscal document line for each ICMS tax fiscal document.</P>



10. On the **Action Pane**, click **Post**, and then, in the **Post fiscal document** form, click **OK** to post the ICMS tax fiscal document. When you post the tax fiscal document, an NF-e XML message is generated and submitted to SEFAZ.

## See also

[(BRA) Create and post an ICMS tax fiscal document](bra-create-and-post-an-icms-tax-fiscal-document.md)

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

  


