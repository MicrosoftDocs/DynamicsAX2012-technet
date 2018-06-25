---
title: Reconcile a bank account
TOCTitle: Reconcile a bank account
ms:assetid: ce12bcc3-074a-403e-85f7-c09f13fd3d49
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa572690(v=AX.60)
ms:contentKeyID: 36971933
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Reconcile a bank account [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you receive a bank statement, you should periodically reconcile legal entity bank transactions with the transactions on the bank statement.

You cannot reconcile a bank statement with a bank account if any of the checks or deposit slip payments that are listed on the statement currently have a status of **Pending cancellation**. After a reviewer posts or rejects a check reversal or deposit slip payment cancellation, the status is no longer **Pending cancellation**, and you can reconcile the bank account. For more information, see [Reverse a posted check](reverse-a-posted-check.md) or [Cancel a deposit slip payment](cancel-a-deposit-slip-payment.md).

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**. Double-click the bank account to reconcile with the bank statement.

2.  On the **Action Pane**, click **Account reconciliation**, and then enter information as appropriate.
    
    You must enter information in the **Bank statement date** and **Bank statement** fields. In the **Ending balance** field, you can enter the balance of the bank account as it appears on the bank statement. For more information, see [Bank statement (form)](https://technet.microsoft.com/en-us/library/aa600290\(v=ax.60\)).

3.  Click **Transactions** to open the **Account reconciliation** form. The upper pane displays the bank account transactions that have not yet been reconciled with a bank statement.
    

    > [!NOTE]
    > <P>To maintain an overview of transactions as you continue, limit or expand the view of the account transactions by changing the value in the <STRONG>Show transactions</STRONG> list.</P>



4.  For each transaction that is included on the bank statement, select the **Cleared** check box if the amount in Microsoft Dynamics AX corresponds to the amount on the bank statement. You can also enter or modify the value in the **Bank transaction type** field. This field value is important for bank transaction statistics and for some reports.
    

    > [!NOTE]
    > <P>Do not select the <STRONG>Cleared</STRONG> check box for transactions that are not on the bank statement. These transactions will continue to be displayed in this form until they are reconciled with a future bank statement.</P>
    > <P>The <STRONG>Cleared</STRONG> check box is not available if the transaction has a status of <STRONG>Pending cancellation</STRONG>. Transactions might have this status if Microsoft Dynamics AX is set up to require that reversals or cancellations be sent to review before they are posted. After a reviewer posts or rejects the reversal or cancellation, the status is no longer <STRONG>Pending cancellation</STRONG>, and you can reconcile the bank account with the bank statement. For more information, see <A href="set-up-a-review-process-for-reversals-and-cancellations.md">Set up a review process for reversals and cancellations</A>.</P>

    
    To select the **Cleared** check box for an interval of checks that all are displayed on the bank statement, click **Mark check interval**, and then indicate the interval.

5.  If the amount for a bank account transaction does not correspond to the amount for the transaction on the bank statement, enter the amount of the correction in the **Correction amount** field, enter an offset main account for the correction amount in the **Main account** field, and then enter explanatory information in the **Description** field.
    

    > [!NOTE]
    > <P>If the fiscal period of the transaction to be corrected is closed, the <STRONG>Correction amount</STRONG> field cannot be used. Instead, create a line that has a transaction date that is in an open fiscal period for the correction. In this case, you must add the financial dimensions that were used on the original transaction, and also the offset main account and the description.</P>



6.  Create transactions for entries, such as fees and interest, that are on the bank statement, but that are not recorded in Microsoft Dynamics AX. Enter the offset main account, description, and appropriate financial dimensions.

7.  As the transactions on the bank statement are marked as **Cleared**, the amount in the **Unreconciled** field, which is recalculated continuously as you make changes, approaches zero. When it reaches zero, click **Reconcile account** to post the reconciliation, and the transactions and corrections that you have created.
    
    After the reconciliation is posted, the transactions that have been included cannot be modified or corrected, and they are not displayed for future account reconciliation.

8.  To view bank transactions that have not yet been reconciled, use the **Unreconciled bank transactions** report. To view the bank statement for a bank account, use the **Bank statement** report.

## See also

[Account reconciliation (form)](https://technet.microsoft.com/en-us/library/aa597523\(v=ax.60\))

[Cancel a deposit slip payment](cancel-a-deposit-slip-payment.md)

[Reverse a posted check](reverse-a-posted-check.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

