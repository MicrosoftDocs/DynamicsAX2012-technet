---
title: (POL) Set up bank parameters
TOCTitle: (POL) Set up bank parameters
ms:assetid: fd4779fa-5942-405a-bed5-bd3a76f3fb46
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711337(v=AX.60)
ms:contentKeyID: 49387154
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up bank parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a method to calculate exchange rate differences in the **Cash and bank management parameters** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  In the **Cash and bank management parameters** form, click the **General** link. On the **General** tab, in the **Exchange differences type** field, select one of the following calculation methods:
    
      - **FIFO** - Settle expenditure transactions that have an earlier transaction date, with earlier receipt transactions according to the first in, first out principle.
    
      - **LIFO** - Settle expenditure transactions that have a more recent transaction date, with later receipt transactions according to the last in, first out principle.
    

    > [!NOTE]
    > <P>Only those bank transactions that are assigned the same registration currency code are settled.</P>



3.  Click the **Number sequences** link. In the **Number sequence code** field, select a number sequence code for the **Bank - Exchange adjustment (FIFO/LIFO)** reference type. This number sequence is assigned automatically when you post exchange rate adjustments to the general ledger.

## See also

[(POL) Cash and bank management parameters (modified form)](https://technet.microsoft.com/en-us/library/jj711286\(v=ax.60\))

[Cash and bank management parameters (form)](https://technet.microsoft.com/en-us/library/aa591289\(v=ax.60\))

[(POL) Set up ledger accounts for posting currency exchange differences](pol-set-up-ledger-accounts-for-posting-currency-exchange-differences.md)

[(POL) Revalue foreign currency amounts for bank transactions](pol-revalue-foreign-currency-amounts-for-bank-transactions.md)

  


