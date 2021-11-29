---
title: (IND) Split purchase transactions based on delivery information
TOCTitle: (IND) Split purchase transactions based on delivery information
ms:assetid: 8f2bb2fb-b3f4-4e3d-992b-d322a8efd8df
ms:mtpsurl: https://technet.microsoft.com/library/JJ678049(v=AX.60)
ms:contentKeyID: 49386012
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Split purchase transactions based on delivery information 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In a purchase transaction, you can split purchase orders, packing slips, and vendor invoices. These documents can be split based on delivery addresses and tax account numbers (TAN). If a purchase order, packing slip, or vendor invoice includes multiple delivery addresses and multiple registration numbers, you can split it into as many multiples of those same documents.

For example, four purchase orders have the following details for multiple addresses and tax account numbers:

  - Purchase order 1: address 1, TAN 1

  - Purchase order 2: address 2, TAN 2

  - Purchase order 3: address 1, TAN 3

  - Purchanse order 4: address 4, TAN 4

When each purchase order is split based on delivery addresses, the following invoices are posted:

  - Invoice 1: posted for purchase order 1 and purchase order 3

  - Invoice 2: posted for purchase order 2

  - Invoice 3: posted for purchase order 4

### Split purchase transactions based on delivery information

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click **Updates**.

3.  In the **Split based on delivery information** group, select the check box for the document or documents that you want to base the split on:
    
      - **Product receipt** – Select this check box to generate a product receipt that has multiple delivery addresses and multiple TANs. The product receipt is split based on the number of delivery addresses and TANs.
    
      - **Invoice** – Select this check box to generate an invoice that has multiple delivery addresses and multiple TANs. The invoice is split based on the number of delivery addresses and TANs.
    

    > [!NOTE]
    > <P>If you do not select either check box, only one purchase order is issued even if the delivery addresses are different.</P>



## See also

[(IND) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj664793\(v=ax.60\))

  


