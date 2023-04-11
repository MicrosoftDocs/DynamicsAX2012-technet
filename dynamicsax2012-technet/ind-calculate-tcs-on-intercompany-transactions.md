---
title: (IND) Calculate TCS on intercompany transactions
TOCTitle: (IND) Calculate TCS on intercompany transactions
ms:assetid: 6c840ed2-295c-494e-aeba-479a9b297dec
ms:mtpsurl: https://technet.microsoft.com/library/JJ677898(v=AX.60)
ms:contentKeyID: 49385861
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate TCS on intercompany transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can calculate Tax Collected at Source (TCS) on intercompany transactions. TCS is calculated in the following phases in intercompany transactions:

  - When you create an intercompany sales order or purchase order, the default TCS group that is defined for the customer or vendor is used to calculate TCS. The TCS amount is posted to the recoverable or payable accounts after the invoice is posted.

  - A sales order or a purchase order is automatically created in the intercompany for the original sales order or purchase order. The default TCS group to calculate TCS for also is displayed in the order and can be changed. If the total invoice amount, including the TCS amount of the automatically created order does not match the total invoice amount of the original order, the invoice cannot be posted.
    
    For example, a sales invoice is created for INR 50,000. A TCS group—10%—is attached to the invoice. The posted invoice amount is INR 50,000 and the posted TCS amount is INR 5,000 for the sales invoice. A purchase order is automatically created for the sales order in the intercompany with the 10% TCS group. If you change the TCS group to 15%, you cannot post the invoice because the total invoice amount of the order does not match the total invoice amount of the original order.

  - When you create a payment journal for an intercompany invoice, a payment journal is posted automatically in the intercompany. If the total payment amount of the payment journal does not match the total payment amount of the original payment journal, the payment journal cannot be posted.

  


