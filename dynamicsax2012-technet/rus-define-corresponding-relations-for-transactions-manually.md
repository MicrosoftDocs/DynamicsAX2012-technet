---
title: (RUS) Define corresponding relations for transactions manually
TOCTitle: (RUS) Define corresponding relations for transactions manually
ms:assetid: bdffab7d-3070-4835-b632-77e736d70c39
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711560(v=AX.60)
ms:contentKeyID: 49387884
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Define corresponding relations for transactions manually 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the manual transaction correspondence function to define a relationship between non-corresponding transactions. When the account correspondence mechanism is turned off in the ledger, all transactions are generated normally. No correspondence link is established between accounts. The function is not retroactive. When correspondence is turned back on, correspondence will not be established for transactions that were performed earlier.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Periodic** \> **Manual correspondence**.

2.  In the left pane view the list of posted vouchers.

3.  On the **Overview** tab to view the voucher transaction.

4.  In the **Show only vouchers** field, select the vouchers to view from the following options:
    
      - **Not corresponded** − View vouchers with no corresponding ledger transactions.
    
      - **Corresponded** − View vouchers with corresponding ledger transactions.
    
      - **All** − View all vouchers.

5.  Click the **Offset** tab.

6.  In the upper pane, select a line under the **Debit transactions** and **Credit transactions** field groups and then click **\<-\>** to correspond, or link, a debit and a credit transaction and move them to the lower pane as a corresponded transaction.
    

    > [!NOTE]
    > <P>You can also drag one transaction over the other to move them to the lower pane as a corresponded transaction.</P>



7.  Click **\<\<-\>\>** to correspond the relationships of all credit and debit vouchers for the selected voucher automatically.

8.  Click **Save** to save the results, or click **Restore** to cancel the last modifications.

9.  Click the **Refresh data** button to refresh the data in the **Manual correspondence** form.
    

    > [!NOTE]
    > <P>After refreshing the data, the voucher for which correspondence has been established will appear in the list of corresponded vouchers.</P>



10. To remove the corresponding relationships for a voucher, select the voucher in the left pane, click **Remove ledger bond**, and then click **Refresh data**.
    

    > [!NOTE]
    > <P>After refreshing the data, the voucher for which correspondence has been removed will appear in the list of non-corresponded vouchers.</P>



## See also

[(RUS) Manual correspondence (form)](https://technet.microsoft.com/en-us/library/jj733174\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

