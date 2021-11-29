---
title: (RUS) Complete the settlement for an advance holder
TOCTitle: (RUS) Complete the settlement for an advance holder
ms:assetid: d06201ec-9290-45b9-9832-3c3be736d735
ms:mtpsurl: https://technet.microsoft.com/library/JJ711641(v=AX.60)
ms:contentKeyID: 49387965
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Complete the settlement for an advance holder
audience: Application User
ms.search.region: Russia
---

# (RUS) Complete the settlement for an advance holder 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can complete a manual settlement or periodic settlement for an advance holder. If you clear the **Automatic settlement** check box in the **Accounts payable parameters** form, you must settle the posting or closing transactions manually, or by using the periodic settlement function.

## Settle advance holder transactions manually

Use this procedure to settle advance holder transactions manually.

1.  Click **Accounts payable** \> **Common** \> **Advance holders** \> **Advance holders**.

2.  Select an advance holder.

3.  Click **Functions** \> **Settle open transactions** to open the **Open-transaction editing in several currencies** form. The upper pane displays debit transactions for an advance holder, and the lower pane displays credit transactions.

4.  In the upper and lower panes, select the **Mark** check box to select the transactions. The **Balance** field displays the balances after the transactions are settled.

5.  Click **Update** to complete the settlement.

6.  Close the form.

7.  In the **Advance holders** form, click **Settlements** to open the **Transaction settlements** form. You can verify the completed settlements in this form.
    

    > [!NOTE]
    > <P>If exchange adjustments occur when advance holder transactions are settled, exchange adjustment transactions are generated from the settlement. The exchange rate adjustment is displayed in the <STRONG>Exchange rate adjustment amount</STRONG> field in the <STRONG>Transaction settlements</STRONG> form.</P>



8.  Close the form.

9.  Click **Accounts payable** \> **Common** \> **Advance holders** \> **Advance reports**.

10. Double-click the advance report that is created for the selected advance holder.

11. On the **Financials** tab, click **View distributions** to verify that the distribution of the expense amount is correct.

## Settle advance holder transactions periodically

Use this procedure to settle advance holder transactions periodically. When you use the periodic settlement function, all open transactions are settled in chronological order.

1.  Click **Accounts payable** \> **Periodic** \> **Advance holders** \> **Periodic settlement**.

2.  In the **Date of transaction.** field, select the advance holder transaction date. All transactions that are posted before this date are settled.

3.  Select the **Settlement by profile** check box to settle transactions that have identical posting profiles.

4.  Click **Select** to open the supplementary request setup to search for transactions for settlement.

5.  Click **OK** to settle the transactions.

## Cancel a periodic settlement

Use this procedure to cancel a periodic settlement for advance holder transactions.

1.  Click **Accounts payable** \> **Periodic** \> **Advance holders** \> **Periodic reverse**.

2.  In the **Date of transaction.** field, select the advance holder transaction date. All transactions that are settled before this date are reversed.

3.  Click **Select** to open the supplementary request setup to search for transactions to cancel the settlements for.

4.  Click **OK** to cancel the periodic settlement.

## See also

[(RUS) Periodic reverse (form)](https://technet.microsoft.com/library/jj678637\(v=ax.60\))

[(RUS) Advance holders (form)](https://technet.microsoft.com/library/jj665294\(v=ax.60\))

[(RUS) Transaction settlements (form)](https://technet.microsoft.com/library/jj711614\(v=ax.60\))

[(RUS) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj923609\(v=ax.60\))

  


