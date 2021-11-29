---
title: Create ledger accrual transactions
TOCTitle: Create ledger accrual transactions
ms:assetid: b6cf8cec-83b1-456a-ba3f-de8310c4b684
ms:mtpsurl: https://technet.microsoft.com/library/Aa572155(v=AX.60)
ms:contentKeyID: 36059098
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create ledger accrual transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a line.

3.  Click **Lines**.

4.  In the **Journal voucher** form, press CTRL+N to create a journal line, select a ledger account, enter an amount to be accrued, and then optionally select an offset account.

5.  Click **Functions**, and then click **Ledger accruals**.

6.  In the **Ledger accruals** form, select the accrual identification that you want to process.

7.  Optionally, change the amount in the **Base amount** field, which is the amount from the journal lines minus the sales tax amount, because sales taxes are not accrued.

8.  Enter the starting date for the first accrued transaction. The date from the journal line is the default date. The **End date** field is automatically filled in based on the configuration in the **Accrual schemes** form, and changes according to the starting date.

9.  Select whether the account or the offset account on the journal line is the account to be accrued. The accounts defined in the **Accrual schemes** form are used as offset accounts for the accrual transactions.

10. Click **Transactions** to verify the generated accrual transactions.

11. Close the **Ledger accrual transactions** form and the **Ledger accruals** form.

12. Post the journal.

13. Click **Inquiries**, and then click **Voucher** to verify the main transactions on the journal line.

14. Click **Origin** to verify the generated accrual transactions.

## See also

[Ledger accruals (form)](https://technet.microsoft.com/library/aa574924\(v=ax.60\))

[Accrual schemes (form)](https://technet.microsoft.com/library/aa597492\(v=ax.60\))

  


