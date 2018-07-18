---
title: (RUS) Create and post a payment journal line for an advance holder
TOCTitle: (RUS) Create and post a payment journal line for an advance holder
ms:assetid: a75dfb35-2aca-453d-b518-037f5d6abbb9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853214(v=AX.60)
ms:contentKeyID: 50396495
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post a payment journal line for an advance holder 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you create and post a payment journal line for an advance holder, complete the following tasks:

  - Create and post a payment journal for the advance holder.

  - Calculate the exchange rate adjustment for the advance holder.
    

    > [!NOTE]
    > <P>The periodic process for exchange adjustment does not include the advance transactions. Therefore, advances are not revalued.</P>



  - Create and post an advance report. For more information, see [(RUS) Generate and post advance report lines manually](rus-generate-and-post-advance-report-lines-manually.md), [(RUS) Advance reports (form)](https://technet.microsoft.com/en-us/library/jj733237\(v=ax.60\)), and [(RUS) Generate and post a facture for an advance report](rus-generate-and-post-a-facture-for-an-advance-report.md).

  - Settle the advance payment that is issued to the advance holder. For more information, see [(RUS) Complete the settlement for an advance holder](rus-complete-the-settlement-for-an-advance-holder.md).

  - Verify the advance adjustment transaction that is created, in the **Advance holder transactions** form. (Click **Accounts payable** \> **Common** \> **Advance holders** \> **Advance holders**. Double-click an advance holder and click **Transactions**.) You can verify the general ledger transactions in the **Voucher transactions** form. (Click **Accounts payable** \> **Common** \> **Advance holders** \> **Advance holders**. Double-click an advance holder, click **Transactions**, and then click **Voucher**.)

  - Print the advance report.

  - Create and post a tax register journal. For more information, see [(RUS) Create and post a tax register journal](rus-create-and-post-a-tax-register-journal.md).

  - View the advance holder balances and transactions in the **Advance holder turnover register** form. For more information, see [(RUS) Balance turnover register (employees) (form)](https://technet.microsoft.com/en-us/library/jj711437\(v=ax.60\)).

Use this procedure to create and post a payment journal for an advance holder.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new general journal.

3.  Click **Lines** to open the **Journal voucher** form.

4.  In the **Date** field, select the posting date.

5.  In the **Account type** field, select **Advance holder** as the account type.

6.  In the **Account** field, select the account number for the employee.

7.  In the **Debit** field, enter a debit amount for the transaction.

8.  In the **Offset account type** field, select **Bank**. In the **Offset account** field, select the offset account number.

9.  In the **Currency** field, select a currency for the transaction.

10. Click **Validate** \> **Validate** to validate the journal voucher.

11. Click **Post** \> **Post** to post the journal voucher.

## See also

[(RUS) Set up advance adjustment parameters for advance holders](rus-set-up-advance-adjustment-parameters-for-advance-holders.md)

  


