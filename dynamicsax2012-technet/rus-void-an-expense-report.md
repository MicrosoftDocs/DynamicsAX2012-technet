---
title: (RUS) Void an expense report
TOCTitle: (RUS) Void an expense report
ms:assetid: 7e11114b-dc8d-41f0-b72a-51a13e5faf2f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678399(v=AX.60)
ms:contentKeyID: 49387629
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Void an expense report
---

# (RUS) Void an expense report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can void expense reports that have been posted, and for which the status of the advance report is **Posted**. These reports should not have been settled. Factures are not created for these reports.

1.  Click **Accounts payable** \> **Common** \> **Advance holders** \> **Advance reports**.

2.  Select the advance report to void.

3.  Click **Rejection**. The status of the advance report is set to **Rejected**.
    

    > [!NOTE]
    > <P>When an advance report is rejected, reversed transactions are created for the advance holder. The <STRONG>Reversed</STRONG> check box is automatically selected in the <STRONG>Advance holder transactions</STRONG> form. The transactions are settled and reversed automatically.</P>



4.  Close the form.

5.  Click **Accounts payable** \> **Common** \> **Advance holders** \> **Advance holders**. Click **Transactions** to open the **Advance holder transactions** form.

6.  Click **Voucher**, and verify that the **Correction** check box is selected
    
    You can verify the distribution of expenses for the reversed transaction. Reversed or storno accounting transactions are distributed like the original transactions. However, the distributions for reversed or storno accounting transactions have a negative sign.

## See also

[(RUS) Advance reports (form)](https://technet.microsoft.com/en-us/library/jj733237\(v=ax.60\))

[(RUS) Advance holder transactions (form)](https://technet.microsoft.com/en-us/library/jj733234\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

