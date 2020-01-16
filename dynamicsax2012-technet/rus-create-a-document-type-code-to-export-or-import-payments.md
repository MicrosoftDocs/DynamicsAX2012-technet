---
title: (RUS) Create a document type code to export or import payments
TOCTitle: (RUS) Create a document type code to export or import payments
ms:assetid: 1f884b14-374d-45c6-a45c-50af459aff99
ms:mtpsurl: https://technet.microsoft.com/library/JJ711456(v=AX.60)
ms:contentKeyID: 49387270
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- import
- export
- document type
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a document type code to export or import payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Document type** form to create a code for a document type that you can use to export or import payments. The document type is used to identify the payment files when you export or import payments. Document type codes are used to identify incoming and outgoing payments. These payments are posted to bank accounts for the selected payment document types. A unique two-digit code is assigned to every type of document. For example, 01 can be used for payment orders, and 09 can be used for memorial slips.

1.  Click **Cash and bank management** \> **Setup** \> **Payment order** \> **Kinds of documents**.

2.  Press CTRL+N to create a new document type code.

3.  In the **The code of document kind** field, enter a two-digit document code. For example, enter 01 for payment orders.

4.  In the **Description** field, enter the name of the document.

5.  In the **Document type** field, select the type of document:
    
      - **Pay document** – Create a payment order, which includes a payment transaction for import or export to the client bank.
    
      - **Memorial order** – Create a memorial slip. A memorial slip is a primary document that the bank uses to transfer money from a cash account to a bank account, or from a bank account to a cash account.
    
      - **Currency transfer** – Create a currency transfer order.
    
      - **Currency sale** – Create a currency sale when you sell foreign currency for business transactions.
    
      - **Currency purchase** – Create a currency purchase transaction when you transfer foreign currency for business transactions.

## See also

[(RUS) Document type (form)](https://technet.microsoft.com/library/jj665436\(v=ax.60\))

  


