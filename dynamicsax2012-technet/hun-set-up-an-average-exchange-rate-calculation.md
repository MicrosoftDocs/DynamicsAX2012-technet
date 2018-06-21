---
title: (HUN) Set up an average exchange rate calculation
TOCTitle: (HUN) Set up an average exchange rate calculation
ms:assetid: 2579c3e3-aa06-4214-8231-44e91475e215
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664239(v=AX.60)
ms:contentKeyID: 49385328
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HUN) Set up an average exchange rate calculation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the calculation of exchange rates for journal lines. For cash and bank transactions, you can use either the daily exchange rate or an average exchange rate. For petty cash and bank journal lines, the calculation of the average exchange rate uses the summarized amounts of the accounting currency and the foreign currency before the specified transaction date.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Click **New** to create a journal.

3.  Click **Lines** to open the **Journal voucher** form.

4.  In the **Account type** field, select **Bank**, **Petty cash**, or **Ledger**.

5.  Click **Functions** \> **Exchange rate calculation** to open the **Exchange rate calculation** form.

6.  In the **From date** field, select a transaction date to specify a period. Ledger transactions are included in the calculation of the average exchange rate if the transaction dates are on or after the date that you enter in this field, and before the transaction date of the journal line. If you leave this field blank, the calculation includes all ledger transactions for which the transaction dates are before the transaction date of the journal line.

7.  In the **Calculation method** field, select **Average exchange rate**.

8.  Click **Select** to open the **Inquiry** form. Then set up selection criteria for the lines to include in the exchange rate calculation. If you do not set up selection criteria in the **Inquiry** form, the calculation method that you selected is used for all lines in the current journal.

9.  Click **OK** to return to the **Exchange rate calculation** form.

10. Click **OK** to close the form. The exchange rate calculation is used by slip journals and by general journals that have petty cash lines.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

