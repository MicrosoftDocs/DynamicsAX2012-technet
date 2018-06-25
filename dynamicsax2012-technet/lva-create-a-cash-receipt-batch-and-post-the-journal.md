---
title: (LVA) Create a cash receipt batch and post the journal
TOCTitle: (LVA) Create a cash receipt batch and post the journal
ms:assetid: 7d5ffb08-67de-4053-b3b4-03979f982765
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838782(v=AX.60)
ms:contentKeyID: 50120664
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LVA) Create a cash receipt batch and post the journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Cash receipt books** form to create cash receipts that you can use during transactions.

1.  Click **General ledger** \> **Periodic** \> **Cash receipts management** \> **Cash receipts**.

2.  Press CTRL+N to create a new line, and enter the required details.

3.  In the **Acquisition date** field, select the date that the tax authority registered the cash receipts.

4.  In the **Format** field, specify the format.

5.  In the **From** field, enter the smallest receipt number in the batch.

6.  In the **To** field, enter the largest receipt number in the batch.

7.  Click **Acquisition** to register the cash receipt batch.
    

    > [!NOTE]
    > <P>When you click <STRONG>Acquisition</STRONG>, the value in the <STRONG>Status</STRONG> field changes to <STRONG>Acquired</STRONG>.</P>



8.  Click **Movements** to open the **Movements** form.

9.  Click **New** to create a new line.

10. In the **Date** field, enter the date to report the transaction.

11. In the **From** field, enter the smallest receipt number in the batch.

12. In the **To** field, enter the largest receipt number in the batch.

13. In the **Responsible** field, select the identifier of the employee who is responsible for the cash receipts transactions.
    

    > [!NOTE]
    > <P>When the <STRONG>Movements</STRONG> form is closed, the value in the <STRONG>Status</STRONG> field in the <STRONG>Cash receipt books</STRONG> form changes to <STRONG>In use</STRONG>.</P>



14. Click **Transactions** to open the **Transactions** form.

15. In the **Date** field, enter the date to report the transaction.

16. In the **Type** field, select the type of cash receipt transactions. The options are **Movement**, **Used**, and **Voided**.

17. In the **From** field, enter the smallest receipt number in the batch.

18. In the **To** field, enter the largest receipt number in the batch.

19. In the **Amount in local currency** field, enter the transaction amount.

20. Click **General ledger** \> **Reports** \> **Transactions** \> **Cash receipts usage report**. Click **OK** to print the cash receipt usage report.
    

    > [!NOTE]
    > <P>Click <STRONG>Cash and bank management</STRONG> &gt; <STRONG>Journals</STRONG> &gt; <STRONG>Slip journal</STRONG>. Click <STRONG>Lines</STRONG> to open the <STRONG>Journal voucher</STRONG> form. On the <STRONG>Cash order</STRONG> tab, in the <STRONG>Cash receipt number</STRONG> field, enter the cash receipt number. In the <STRONG>Cash receipts</STRONG> field, select the cash receipt batch. You can also click <STRONG>Functions</STRONG> &gt; <STRONG>Transactions</STRONG> to open the <STRONG>Cash transaction</STRONG> form, and then click <STRONG>Cash receipt number</STRONG> to set up cash receipt information.</P>



## See also

[(LVA) Cash receipt books (form)](https://technet.microsoft.com/en-us/library/jj838785\(v=ax.60\))

[(LVA) Cash receipts transactions (form)](https://technet.microsoft.com/en-us/library/jj838783\(v=ax.60\))

[(LVA) Cash receipts movements (form)](https://technet.microsoft.com/en-us/library/jj838784\(v=ax.60\))

[(LVA) Cash receipt update (form)](https://technet.microsoft.com/en-us/library/jj721416\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

