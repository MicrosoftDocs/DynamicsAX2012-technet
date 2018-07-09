---
title: (RUS) Amortize an unrecoverable debt in Accounts receivable
TOCTitle: (RUS) Amortize an unrecoverable debt in Accounts receivable
ms:assetid: dab3a3b8-2f11-4562-9ec1-04a2adc3918f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711662(v=AX.60)
ms:contentKeyID: 49387986
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Amortize an unrecoverable debt in Accounts receivable [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can amortize unrecoverable debt, you must create the register journal for the period during which the amortization is run, and calculate and approve the Accounts receivable – reserves.

After the amortization records are updated, the total amount of the transactions equals the minimum of the marked lines total of unrecoverable debt and reserve amount of doubtful debt.

If the unrecoverable debt total exceeds the amount of the reserve, transactions are created to amortize debt in the unrealized expense and revenue accounts to cover the remaining amount. The created transactions are automatically settled with the unrecoverable accounts and issued advance payments, and therefore, unrecoverable accounts receivable is settled. The voucher amortization date is the same as the date that is specified in the **Calculation date** field.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Periodic** \> **Amortization** \> **Accounts receivable amortization**.

2.  Select the **Mark** check box to select the entries to be amortized. You can view the total for the marked lines in the **Total** field under the **Marked** field group.
    

    > [!NOTE]
    > <P>Transactions are created in the ledger per customer and numbered in accordance with the sequence that is designated for amortizing unrecoverable debt.</P>



3.  Click **Update** to update the total amount for the records selected for amortization. You can view the total that is written off from the reserve or in excess of the reserve in the **From reserve for account receivable** and **To revenues/expenses account** fields.
    

    > [!NOTE]
    > <P>To view the original transactions, click <STRONG>Transaction</STRONG> under <STRONG>Customers</STRONG> to open the <STRONG>Customer transactions</STRONG> form.</P>



4.  Press CTRL+S or close the form.

## See also

[(RUS) AR amortization (form)](https://technet.microsoft.com/en-us/library/jj841091\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

