---
title: (IND) Verify and settle duty drawback voucher transactions
TOCTitle: (IND) Verify and settle duty drawback voucher transactions
ms:assetid: a8231b44-1000-47d1-8fc4-388ed52acc0c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664749(v=AX.60)
ms:contentKeyID: 49386080
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- DBK voucher transactions
- Verify DBK
---

# (IND) Verify and settle duty drawback voucher transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The EXIM duty drawback process generates duty drawback lines. When you process the duty drawback lines, duty drawback voucher transactions are generated. You can use the **EXIM Duty Drawback schemes** form to view the duty drawback voucher transactions. After you verify the amounts for the duty drawback, you can settle the duty drawback transactions and record the accounting entries in the general ledger.

To view this form, you must select the **Duty drawback** check box in the **DBK** area in the **Incentive scheme parameters** form.

For more information about how to generate duty drawback lines and apply for duty drawback for an export order, see [(IND) Apply for duty drawback (DBK) for an export order](ind-apply-for-duty-drawback-dbk-for-an-export-order.md).

## Verify duty drawback transactions

1.  Click **General ledger** \> **Common** \> **EXIM Duty Drawback schemes**.

2.  In the **EXIM Duty Drawback schemes** form, click **Details**.

3.  In the **Transaction vouchers** form, view the duty drawback voucher transactions that were generated when you ran the process to apply for duty drawback.
    

    > [!NOTE]
    > <P>If the voucher was created through the periodic process for EXIM duty drawback, the <STRONG>Status</STRONG> field is set to <STRONG>Drawback</STRONG>. If the voucher was created from the <STRONG>EXIM Duty Drawback schemes</STRONG> form, the status is set to <STRONG>Payment</STRONG>.</P>



4.  Click **Voucher**.

5.  In the **Voucher transactions** form, view the journal transactions that were generated for the duty drawback lines in the general ledger.

## Settle duty drawback transactions on receipt of payment

1.  Click **General ledger** \> **Common** \> **EXIM Duty Drawback schemes**.

2.  On the **Overview** FastTab, select a row, and then click the **General** FastTab.

3.  In the **Drawback letter number** field, enter the number of the drawback letter that was provided by the Directorate General of Foreign Trade (DGFT) authority.

4.  In the **Text** field, enter a description of the duty drawback.

5.  Click **Transactions**.

6.  In the **Duty drawback transactions** form, view the total amount of drawback that is allowed and the total amount of drawback that must be settled. The **Overview** FastTab displays all the duty drawback transactions that you selected when you applied for the duty drawback. By default, all the transactions are selected in the list.

7.  The total that is displayed in the **Amount to settle** field includes only transactions that are selected in the list. If payment has not yet been received for a transaction that is selected in the list, clear the **Select** check box for that transaction.
    
    To clear the check box for all selected transactions in the list, click **No to all**.

8.  In the **Amount to settle** field, you can modify the value of the selected transactions.

9.  Click **Post** to perform the following actions:
    
    1.  Record the duty drawback settlement transactions to the general ledger accounts.
    
    2.  Update the status of the paid transaction lines to **Closed**.
    
    3.  Update the **Total drawback amount realized** field with the total amount that was recorded.
    
    Transactions that are partially paid, and that therefore have a balance that is more than 0 (zero), remain in the **Open transactions** form for the customer, if the customer is specified in the **Customer account** field in the **EXIM ports** form. For more information about open transactions for customers, see [Closed customer transaction editing in several currencies (form)](https://technet.microsoft.com/en-us/library/aa554466\(v=ax.60\)).
    

    > [!NOTE]
    > <P><STRONG>Post</STRONG> is available only when the <STRONG>Amount to settle</STRONG> field is updated with a value other than 0 (zero), and when the <STRONG>Status</STRONG> field is set to <STRONG>Applied</STRONG> for all transactions.</P>



## See also

[(IND) Transactions vouchers (form)](https://technet.microsoft.com/en-us/library/jj678065\(v=ax.60\))

[(IND) Duty Drawback transactions (form)](https://technet.microsoft.com/en-us/library/jj664913\(v=ax.60\))

[(IND) EXIM Duty Drawback schemes (form)](https://technet.microsoft.com/en-us/library/jj664529\(v=ax.60\))

[(IND) Apply for duty drawback (DBK) for an export order](ind-apply-for-duty-drawback-dbk-for-an-export-order.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

