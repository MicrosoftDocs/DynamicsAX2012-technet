---
title: (BRA) Create and post an ICMS tax fiscal document
TOCTitle: (BRA) Create and post an ICMS tax fiscal document
ms:assetid: 392994f5-3e38-459c-b4dd-58450f16a8f4
ms:mtpsurl: https://technet.microsoft.com/library/JJ710463(v=AX.60)
ms:contentKeyID: 49384355
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- ICMS tax document
- tax document
- post and print
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post an ICMS tax fiscal document 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post an Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax fiscal document to transfer an ICMS tax amount between fiscal establishments, or to recover the ICMS tax amount in installments for the purchase of fixed assets.

You can create and post the following types of ICMS tax fiscal documents:

  - Outgoing ICMS tax fiscal document – Transfer the ICMS tax amount to another fiscal establishment.

  - Incoming ICMS tax fiscal document – Receive the ICMS tax amount from another fiscal establishment, or recover the ICMS tax amount in installments for the purchase of fixed assets.

You can create only one ICMS fiscal document line for each ICMS tax fiscal document. You cannot delete a posted ICMS tax fiscal document.


> [!NOTE]
> <P>The fiscal establishment that receives the ICMS tax credit or debit must be set up as a customer or vendor.</P>



1.  Click **General ledger** \> **Journals** \> **All tax fiscal documents**.

2.  On the **Action Pane**, click **Tax fiscal document** to open the **Tax fiscal document** form.

3.  Click the **Tax fiscal document header** FastTab, and then in the **Tax fiscal document type** field, select one of the following options to indicate the type of ICMS tax fiscal document:
    
      - **ICMS tax transfer** – The ICMS tax fiscal document is used to transfer ICMS tax between fiscal establishments.
    
      - **ICMS installment** – The ICMS tax fiscal document is used to recover the ICMS tax amount in installments for the purchase of fixed assets.
        

        > [!NOTE]
        > <P>If you select <STRONG>ICMS installment</STRONG>, the <STRONG>Account type</STRONG> and <STRONG>Direction</STRONG> fields are updated to <STRONG>Vendor</STRONG> and <STRONG>Incoming</STRONG>. The <STRONG>Account type</STRONG>, <STRONG>Direction</STRONG>, and <STRONG>Invoice</STRONG> fields are not available.</P>



4.  In the **Fiscal establishment ID** field, select the identification code of the fiscal establishment that receives or issues the ICMS tax fiscal document.

5.  In the **Account type** field, select one of the following options to indicate the type of account:
    
      - **Customer** – The ICMS tax fiscal document is an outgoing ICMS tax fiscal document. The **Direction** field is updated to **Outgoing**, and the **Direction**, **Invoice**, **Document model**, **Series**, and **Specie** fields are not available.
    
      - **Vendor** – The ICMS tax fiscal document is an incoming tax fiscal document. The **Direction** field is updated to **Incoming**, and the **Direction** and **Fiscal document type** fields are not available.
    

    > [!NOTE]
    > <P>The <STRONG>Account type</STRONG> field is available only if you select <STRONG>ICMS tax transfer</STRONG> in the <STRONG>Tax fiscal document type</STRONG> field.</P>



6.  In the **Account number** field, select the customer or vendor account. The **Name** and **Reference** fields are updated with the name and address of the customer or vendor.

7.  In the **Access key** field, enter the access key for the electronic fiscal document (NF-e).
    

    > [!NOTE]
    > <P>This field is available only if the following conditions are met:</P>
    > <UL>
    > <LI>
    > <P>You select <STRONG>ICMS tax transfer</STRONG> in the <STRONG>Tax fiscal document type</STRONG> field.</P>
    > <LI>
    > <P>You select <STRONG>Vendor</STRONG> in the <STRONG>Account type</STRONG> field.</P>
    > <LI>
    > <P>You select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is selected for the document model in the <STRONG>Document model</STRONG> form.</P></LI></UL>



8.  In the **Invoice** field, enter the invoice number for the ICMS tax fiscal document.
    

    > [!NOTE]
    > <P>This field is available only if the following conditions are met:</P>
    > <UL>
    > <LI>
    > <P>You select <STRONG>ICMS tax transfer</STRONG> in the <STRONG>Tax fiscal document type</STRONG> field.</P>
    > <LI>
    > <P>You select <STRONG>Vendor</STRONG> in the <STRONG>Account type</STRONG> field.</P>
    > <LI>
    > <P>You select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is not selected for the document model in the <STRONG>Document model</STRONG> form.</P></LI></UL>



9.  In the **Date** field, specify the invoice date.

10. In the **Fiscal document type** field, select the type of fiscal document. The **Document model**, **Series**, and **Specie** fields are updated with the values that you specified in the **Document model**, **Series**, and **Specie** fields in the **Fiscal document types** form.
    

    > [!NOTE]
    > <P>The <STRONG>Fiscal document type</STRONG> field is available only if you select <STRONG>Customer</STRONG> in the <STRONG>Account type</STRONG> field.</P>



11. In the **Document model** and **Series** fields, select the document model and enter the series code for the ICMS tax fiscal document. If the **Is for NF-e (federal)** check box is selected for the document model in the **Document model** form, the **Access key** field is available and the **Invoice** and **Series** fields are not available.
    

    > [!NOTE]
    > <P>These fields are available only if you select <STRONG>Vendor</STRONG> in the <STRONG>Account type</STRONG> field.</P>



12. In the **Series** field, enter the series for the ICMS tax fiscal document.
    

    > [!NOTE]
    > <P>This field is available only if the following conditions are met:</P>
    > <UL>
    > <LI>
    > <P>You select <STRONG>ICMS tax transfer</STRONG> in the <STRONG>Tax fiscal document type</STRONG> field.</P>
    > <LI>
    > <P>You select <STRONG>Vendor</STRONG> in the <STRONG>Account type</STRONG> field.</P>
    > <LI>
    > <P>You select a document model in the <STRONG>Document model</STRONG> field, and the <STRONG>Is for NF-e (federal)</STRONG> check box is not selected for the document model in the <STRONG>Document model</STRONG> form.</P></LI></UL>



13. In the **Specie** field, select the specie for the ICMS tax fiscal document.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Vendor</STRONG> in the <STRONG>Account type</STRONG> field.</P>



14. To create an ICMS tax fiscal document line, follow these steps:
    
    1.  In the **Tax fiscal document line** area, in the **Item description** field, enter the description of the item for the ICMS tax fiscal document line.
    
    2.  In the **CFOP** field, select the Código Fiscal de Operações e Prestações (CFOP) code for the ICMS tax fiscal document line. The CFOP codes that are available depend on the fiscal establishment, direction, and address of the customer or vendor.
    
    3.  In the **Sales tax code** field, select the sales tax code for the ICMS tax fiscal document line.
    
    4.  In the **Amount** field, specify the tax amount for the ICMS tax fiscal document line.
    
    You can also click **Fiscal document texts** to open the **Fiscal document texts** form, where you can attach fiscal document texts to the ICMS tax fiscal document line. For more information, see [(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md).
    

    > [!NOTE]
    > <P>You can create only one ICMS tax fiscal document line for each ICMS tax fiscal document.</P>



15. On the **Action Pane**, click **Post**, and then in the **Post fiscal document** form, click **OK** to post the ICMS tax fiscal document.

## See also

[(BRA) About ICMS tax fiscal documents](bra-about-icms-tax-fiscal-documents.md)

[(BRA) Tax fiscal document (form)](https://technet.microsoft.com/library/jj710428\(v=ax.60\))

[(BRA) Cancel an ICMS tax fiscal document](bra-cancel-an-icms-tax-fiscal-document.md)

[(BRA) Set up customer posting profiles](bra-set-up-customer-posting-profiles.md)

[(BRA) Set up vendor posting profiles](bra-set-up-vendor-posting-profiles.md)

[(BRA) Set up ledger posting groups for sales tax](bra-set-up-ledger-posting-groups-for-sales-tax.md)

  


