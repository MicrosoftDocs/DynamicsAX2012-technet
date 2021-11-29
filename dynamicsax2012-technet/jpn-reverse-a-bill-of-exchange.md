---
title: (JPN) Reverse a bill of exchange
TOCTitle: (JPN) Reverse a bill of exchange
ms:assetid: 816b3038-5ffe-49cf-bd9b-0436d2ae885a
ms:mtpsurl: https://technet.microsoft.com/library/JJ711079(v=AX.60)
ms:contentKeyID: 49386488
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Reverse a bill of exchange 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can reverse the drawn and redrawn endorsed bills of exchange (BOEs) after vendor invoices are settled. You can also settle the endorsed BOEs during the maturity period if you have not received a non-acceptance message from the vendor. The summary account number from the original transaction is considered for reversal, and the posting entry is created as debit, Endorsed BoE, and credit, accounts payable account.

## Reverse the vendor invoice settlement

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor transaction.

3.  On the **Invoice** tab, click **Closed transaction editing**.

4.  In the **Closed transaction editing in several currencies** form, select a vendor invoice, and then select the **Mark** check box.

5.  Click **Reverse** to reverse the vendor settlements.

## Reverse an endorsed bill of exchange

1.  Click **Accounts receivable** \> **Common** \> **Bill of exchange** \> **Endorse bills of exchange**.

2.  Select an endorsed BOE, and then, on the **Bill of exchanges list** tab, click **Reverse endorsement** to reverse the vendor settlement.
    

    > [!NOTE]
    > <P>You cannot reverse the endorsed BOE if the transaction is settled. You must reverse the vendor settlement before you reverse the endorsement of the BOE.</P>



## Reverse a bill of exchange

1.  Click **Accounts receivable** \> **Common** \> **Bill of exchange** \> **Endorse bills of exchange**.

2.  Select the customer account record that you have selected for endorsement.

3.  On the **Bill of exchanges list** tab, click **Reverse endorsement**. The status is updated from **Endorsed** to **Drawn**.

## See also

[(JPN) Endorse bill of exchange (list page)](https://technet.microsoft.com/library/jj911067\(v=ax.60\))

  


