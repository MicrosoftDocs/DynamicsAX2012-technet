---
title: (BRA) Set up the CFOP matrix
TOCTitle: (BRA) Set up the CFOP matrix
ms:assetid: 527dea5a-464d-4d1f-9c9c-d8ab4d187ddc
ms:mtpsurl: https://technet.microsoft.com/library/JJ933515(v=AX.60)
ms:contentKeyID: 50935127
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the CFOP matrix 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a Código Fiscal de Operações e Prestações (CFOP) matrix that determines the default CFOP code and the default CFOP group to use for different types of transactions and operations. You must create CFOP codes and CFOP groups before you create the CFOP matrix. For more information, see [(BRA) Set up the CFOP codes](bra-set-up-the-cfop-codes.md) and [(BRA) CFOP groups (form)](https://technet.microsoft.com/library/jj923344\(v=ax.60\)).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **CFOP matrix**.

2.  Press CTRL+N to create a CFOP matrix record.

3.  In the **CFOP** field, select a CFOP code.

4.  In the **Transaction type** field, select one of the following options to indicate the type of transactions to which the CFOP code can be assigned:
    
      - **Sales** – The CFOP code can be assigned to sales orders and related transactions.
    
      - **Purchase** – The CFOP code can be assigned to purchase orders and related transactions.
    
      - **Tax fiscal document** – The CFOP code can be assigned to tax fiscal documents.
    
      - **Free text invoice** – The CFOP code can be assigned to free text invoices.
    
      - **Fiscal establishment transfer** – The CFOP code can be assigned to transfer orders that are used to transfer items from one warehouse to another at different fiscal establishments.
    
      - **Third party transfer** – The CFOP code can be assigned to transfer orders that are used to transfer items to a third party.
    
      - **Item requirement** – The CFOP code can be assigned to reserve items for projects.

5.  In the **Operation type**, select the operation type for the CFOP code and the CFOP group.

6.  In the **CFOP group** field, select the identification code of the CFOP group.
    

    > [!NOTE]
    > <P>The CFOP code and operation type specify the CFOP group that is used to determine taxes by using the taxes matrix.</P>



## See also

[(BRA) CFOP codes (form)](https://technet.microsoft.com/library/jj933522\(v=ax.60\))

[(BRA) CFOP matrix (form)](https://technet.microsoft.com/library/jj933496\(v=ax.60\))

[(BRA) Taxes matrix (form)](https://technet.microsoft.com/library/jj923368\(v=ax.60\))

  


