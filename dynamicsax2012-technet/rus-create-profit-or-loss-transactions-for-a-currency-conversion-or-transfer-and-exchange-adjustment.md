---
title: (RUS) Create profit or loss transactions for a currency conversion or transfer and exchange adjustment
TOCTitle: (RUS) Create profit or loss transactions for a currency conversion or transfer and exchange adjustment
ms:assetid: 9a302a8e-29c6-49f0-bb32-bfc1b078e839
ms:mtpsurl: https://technet.microsoft.com/library/JJ923565(v=AX.60)
ms:contentKeyID: 52075412
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create profit or loss transactions for a currency conversion or transfer and exchange adjustment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create a profit or loss transaction for a currency conversion after a currency sale transaction is settled. The transaction type depends on the following factors:

  - If you sold currency for less than the Federal Bank exchange rate, the transaction amount is debited to the conversion profit account and credited to the vendor account.

  - If you sold currency for more than the Federal Bank exchange rate, the transaction amount is debited to the vendor account and credited to the conversion profit account.


> [!NOTE]
> <P>The amount of the currency sale transaction is calculated by using the following formula:</P>
> <P>(Exchange rate on acceptance date – Bank exchange rate) * (Accepted amount / Bank exchange rate)</P>



1.  Click **Cash and bank management** \> **Setup** \> **Bank groups**.

2.  Select a bank line, and then click **Functions** \> **Settle open transactions** to open the **Settle open transactions** form. For more information, see [Open vendor transactions (form)](https://technet.microsoft.com/library/aa551813\(v=ax.60\)).

3.  In the **Settlement posting date** field, select the settlement posting date.

4.  Select the **Mark** check box for each transaction that must be settled, and then click **Update**. The following information is validated:
    
      - The account number that is specified in the **Transit account** field for open debit vendor transactions must match the account number that is specified in the **Bank account (inflow)** field for open credit vendor transactions.
    
      - The bank transaction type that is specified for the currency charge-off must match the transaction type that is specified for the currency-earned transaction.
    
      - The conversion currency that is specified for the currency charge-off must match the currency that is specified for the currency-earned transaction.
    
    Use the **Vendor transactions** form to verify the amount of the vendor transactions. For more information, see [Vendor transactions (form)](https://technet.microsoft.com/library/aa572427\(v=ax.60\)).

5.  Close the **Settle open transactions** form.

6.  In the **Banks** form, click **Functions** \> **Closed transaction editing** to open the **Closed transaction editing in several currencies** form. You can view and reverse transactions that have been settled. For more information, see [Closed vendor transaction editing in several currencies (form)](https://technet.microsoft.com/library/aa556371\(v=ax.60\)).

7.  In the **Settlement reversal posting date** field, select the settlement reversal posting date for the transaction. Select the **Mark** check box for any transactions that must be reversed.

8.  Click **Reverse** to reverse the currency sale transaction. A reversal transaction entry that has a negative value is created in the profit or loss account, and the source vendor transaction for profit or loss is reversed.

## See also

[(RUS) Create and post a payment journal for an exchanged currency](rus-create-and-post-a-payment-journal-for-an-exchanged-currency.md)

[Reverse settlements](reverse-settlements.md)

[(RUS) Banks (form)](https://technet.microsoft.com/library/jj856183\(v=ax.60\))

  


