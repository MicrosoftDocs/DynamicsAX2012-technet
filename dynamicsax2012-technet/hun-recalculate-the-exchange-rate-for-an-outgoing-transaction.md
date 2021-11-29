---
title: (HUN) Recalculate the exchange rate for an outgoing transaction
TOCTitle: (HUN) Recalculate the exchange rate for an outgoing transaction
ms:assetid: 28b274e2-91c9-4c3e-9a4e-8e034ba1a08b
ms:mtpsurl: https://technet.microsoft.com/library/JJ664242(v=AX.60)
ms:contentKeyID: 49385331
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Recalculate the exchange rate for an outgoing transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The exchange rate is automatically updated when you record an incoming transaction, if a valid exchange rate is recorded in the **Exchange rate** form for the selected currency. When you record an outgoing transaction, you can recalculate the exchange rate by specifying a calculation method in the **Exchange rate calculation** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new line and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "General journal lines (form)" in the Applications and Business Processes Help.</P>



3.  Click **Lines**.

4.  Click **Functions** \> **Exchange rate calculation** to open the **Exchange rate calculation** form.

5.  In the **Calculation method** field, select an exchange rate calculation method.
    
      - **Average exchange rate** – The exchange rate for outgoing transactions is calculated based on the average exchange rate defined in the bank parameters form.
    
      - **Daily exchange rate** – The exchange rate for both incoming and outgoing transactions is calculated using the exchange rate stipulated in the exchange rate form.

6.  Click **OK** to run the exchange rate calculation.

## See also

[(HUN) Set up exchange rate calculation and adjustment](hun-set-up-exchange-rate-calculation-and-adjustment.md)

[(HUN) Set up an average exchange rate calculation](hun-set-up-an-average-exchange-rate-calculation.md)

  


