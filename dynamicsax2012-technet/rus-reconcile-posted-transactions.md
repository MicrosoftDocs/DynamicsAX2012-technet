---
title: (RUS) Reconcile posted transactions
TOCTitle: (RUS) Reconcile posted transactions
ms:assetid: 8e4edbd5-b471-495d-9fd4-2aa3fcc0eb31
ms:mtpsurl: https://technet.microsoft.com/library/JJ678473(v=AX.60)
ms:contentKeyID: 49387702
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Reconcile posted transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can reconcile the transactions posted to a bank account.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select a bank account to reconcile. On the **Action Pane**, click **Account reconciliation**.

3.  Press CTRL+N to create a new line.

4.  In the **Bank account statement** form , in the **Bank account statement date** field, select the date of the bank statement.

5.  In the **Bank statement** field, enter the bank statement number.

6.  In the **Ending balance** field, enter the balance shown on the account statement after payments, disbursements, fees, and interest.

7.  Click **Transactions** to open the **Account reconciliation** form.

8.  On the **Posted operations** tab, view the list of transactions that are reconciled in the account statement.

9.  On the **Overview** tab, select the **Cleared** field for each reconciled transaction.
    

    > [!NOTE]
    > <P>If the Reconcile account total of the incoming balance for the bank account equals the ending balance on the statement, the account is balanced, and the <STRONG>Reconcile account</STRONG> option on the <STRONG>Functions</STRONG> button is available.</P>



10. Click **Functions**, and then select **Reconcile account** to complete the operation.
    

    > [!NOTE]
    > <P>After the operations are reconciled in the statement, the status of the bank statement changes to <STRONG>Reconciled</STRONG>.</P>



11. Press CTRL+S or close the form.

12. Open the **Bank account statement** form.

13. In the **View** field, select **Reconciled** to view the reconciled bank statement and the date of reconciliation.
    

    > [!NOTE]
    > <P>To change the operation date for posted bank transactions, you can use the <STRONG>Transit account</STRONG> option on the <STRONG>Functions</STRONG> button in the <STRONG>Account reconciliation</STRONG> form. However, you cannot use this option for transactions with Customer or Vendor type bank accounts.</P>



14. Press CTRL+S or close the form.

## Transactions without payment journal lines

If a bank statement contains a transaction without a corresponding payment journal line, do the following:

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  On the **Number sequences** tab, in the **Reference** field, set up a number sequence code for the **Bank reconciliation** option.

3.  Press CTRL+S or close the form.

4.  In the **Account reconciliation** form, on the **Posted operations** tab, on the **Overview** tab, create a new line.

5.  In the **Bank transaction type** field, select the transaction type.

6.  In the **Account** field, select the account number for posting in ledger.

7.  In the **Date** field, select the date of voucher posting.

8.  In the **Amount in transcation currency** field, enter the amount of posting in currency.

9.  Click **Functions**, and then select **Posting**.
    
    A bank voucher and ledger voucher are generated for a ledger account that is set up for the bank account corresponding to the account in the **Ledger account** field in the **Account reconciliation** form.

## See also

[(RUS) Bank account reconciliation (modified form)](https://technet.microsoft.com/library/jj711451\(v=ax.60\))

[(RUS) Transit account function](rus-transit-account-function.md)

  


