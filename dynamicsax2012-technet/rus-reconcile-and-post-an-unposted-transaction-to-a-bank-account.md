---
title: (RUS) Reconcile and post an unposted transaction to a bank account
TOCTitle: (RUS) Reconcile and post an unposted transaction to a bank account
ms:assetid: c51472eb-ab77-4f61-bc26-3e1d50ba508b
ms:mtpsurl: https://technet.microsoft.com/library/JJ711585(v=AX.60)
ms:contentKeyID: 49387909
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Reconcile and post an unposted transaction to a bank account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The bank statement reflects payments that are made from an account. After you reconcile the bank statement with the payment orders made, the reconciled payments are posted to ledger accounts. The unposted transactions must be managed separately. Also, any payments that are rejected by the bank must be resubmitted or voided.

A payment journal line can have a **Sent**, **Received**, or **Approved** status.

After reconciliation, the date of the payment document and the date of the transaction might differ.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select the bank account to be reconciled.

3.  Click **Functions**, and then select **Account reconciliation** to open the **Bank account statement** form.

4.  Press CTRL+N to create a new line.

5.  Enter information in the **Bank account statement date**, **Bank statement**, and **Ending balance** fields.
    

    > [!NOTE]
    > <P>To correctly calculate the end balance for the bank account, the bank statements must be registered in chronological order.</P>



6.  Click **Transactions** to open the **Account reconciliation** form.

7.  On the **Unposted operations** tab, view the unposted transactions for the bank account in the **Opening balance**, **Ending balance**, **Unreconciled**, **Check number**, and **Amount currency** fields. View the reconciled totals for transactions at the bottom of the form.
    

    > [!NOTE]
    > <P>Incoming payments are denoted by a minus sign (-) and outgoing payments are denoted by a plus sign (+).</P>



8.  In the **Show transactions** field, select one of the following options:
    
      - **All** – Displays all operations for the bank account (reconciled and unreconciled).
    
      - **Unreconciled** – Displays unreconciled operations for the bank account.
    
      - **Reconciled** – Displays reconciled operations for the bank account.

9.  Select the **Cleared** field for payments that have been reconciled based on the bank statement.
    

    > [!NOTE]
    > <P>The status of the payment line changes to <STRONG>Approved</STRONG>. If the <STRONG>Cleared</STRONG> field is not selected, the status of the payment line changes to <STRONG>Sent</STRONG> for vendor payments and if the <STRONG>Check number</STRONG> field is entered the status of the payment line changes to <STRONG>Sent</STRONG> or <STRONG>Received</STRONG> for customer payments.</P>



10. In the **Date** field, specify the payment date as shown in the bank statement if it is different from the payment order date. This date will be the date of the payment transaction.

11. Click the **Functions** button and then select **Reconcile account** to reconcile the operation.
    

    > [!NOTE]
    > <P>You can select this button only if the sum of starting balance and selected transactions equals the manually entered statement end balance.</P>



12. Click **Functions** and then select **Posting**. New payment journals for vendors or customers are created and a dialog box with the codes for the new journals opens.

13. Select the **Delete empty journal** check box to delete the source journal.

14. Click **OK** to post the new payment journals.
    
    Transactions will be generated for an account for writing off or receipt of funds.

15. Open the **Bank account statement** form.

16. In the **View** field, select **Reconciled** to view the reconciled bank statement and the date of reconciliation.

17. In the **Account reconciliation** form, click **Functions** and then select **Posting**. The unreconciled banking operations that are displayed on the **Unposted operations** tab will be posted. The reconciliation in this case can be done for posted banking transactions, reflected on the **Posted operations** tab.
    

    > [!NOTE]
    > <P>To post payments through an interim account, activate the Bridging Posting parameter for the method of payment. When the journal is posted, transactions will be generated in accordance with the transit account. To transfer payments from an interim account to a ledger account, click <STRONG>Functions</STRONG> and then select <STRONG>Select bridged vouchers</STRONG>. A new journal will be generated. After posting the journal, payments will be reflected in the <STRONG>Account reconciliation</STRONG> form on the <STRONG>Posted operations</STRONG> tab and will become accessible to perform bank reconciliations for the posted transactions.</P>



## See also

[(RUS) Bank account reconciliation (modified form)](https://technet.microsoft.com/library/jj711451\(v=ax.60\))

  


