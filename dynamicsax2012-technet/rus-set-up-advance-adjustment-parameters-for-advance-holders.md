---
title: (RUS) Set up advance adjustment parameters for advance holders
TOCTitle: (RUS) Set up advance adjustment parameters for advance holders
ms:assetid: 8d87ae88-39cf-4e5d-a50d-a932b6aae78c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853204(v=AX.60)
ms:contentKeyID: 50396485
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up advance adjustment parameters for advance holders [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The calculation of exchange adjustments on advance payments that are issued or received in currency is no longer required in business accounting.

When you settle advance payments and advance reports, the advance adjustment transaction is created as a continuation of the advance report, based on the setup in the **General ledger parameters** form and the **Advance adjustment parameters** form. The advance adjustment transaction is displayed in the **Advance holder transactions** form. The amounts on the advance report are based on the exchange rate on the advance payment date, not on the posting date.

Complete the following tasks before you settle advances that are issued to an advance holder:

1.  Set up an advance holder. For more information, see [(RUS) Set up the advance holder](rus-set-up-the-advance-holder.md) and [(RUS) Advance holders (form)](https://technet.microsoft.com/en-us/library/jj665294\(v=ax.60\)).

2.  Set up general ledger parameters for exchange adjustment.

Use the following procedure to set up advance adjustment parameters for advance holders.

1.  Click **General ledger** \> **Setup** \> **Advance adjustment parameters**.

2.  Click **Purchases/Advance holders**.

3.  In the **Ledger posting** field, select the type of ledger posting from the following options:
    
      - **Invoice accounts** – Confirm that the advance adjustment that results from the settlement of an advance and an advance report for the advance holder is a continuation of the advance report.
    
      - **Deviation from the cost price** – Confirm that the calculation should be processed according to the settings of the account for deviation, and that the advance adjustment is not a continuation of the advance report. Depending on the advance adjustment type, specific ledger accounts are used for the adjustment of the advance payments.

4.  In the **Realized loss** field, select the ledger account to post an exchange rate loss for an employee to.

5.  In the **Realized gain** field, select the ledger account to post an exchange rate profit for an employee to.
    

    > [!NOTE]
    > <P>The realized loss and realized profit accounts are used for the adjustment of advance payments only if the inventory is closed.</P>



6.  In the **Expense code** field, select a tax dimension expense code.

7.  In the **Revenue code** field, select a tax dimension revenue code.

8.  In the **Advance adjustment - loss** field, select the ledger account to post an advance adjustment loss in tax accounting to.

9.  In the **Advance adjustment - profit** field, select the ledger account to post an advance adjustment profit in tax accounting to.

10. In the **Advance adjustment offset account** field, select the offset ledger account to post an advance adjustment in tax accounting to.

## See also

[(RUS) Advance adjustment parameters (form)](https://technet.microsoft.com/en-us/library/jj853184\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

