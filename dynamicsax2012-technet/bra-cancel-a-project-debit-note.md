---
title: (BRA) Cancel a project debit note
TOCTitle: (BRA) Cancel a project debit note
ms:assetid: 5d78316a-01a2-45dc-b639-286fda27ba16
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ916623(v=AX.60)
ms:contentKeyID: 50934013
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project debit note
- cancel a debit note
- debit note
---

# (BRA) Cancel a project debit note 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Debit note journals** form to cancel debit notes for a project.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project line, and then on the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **Debit note journals**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Project debit notes** \> **Project debit note journals**.

2.  Select a debit note to cancel, and then click **Functions** \> **Debit note cancellation**.

3.  Click **Yes**.

4.  In the **Reason code** field, select a reason code for the cancellation of the debit note.

5.  In the **Comments** field, enter additional information about the cancellation of the debit note.

6.  In the **Cancelling debit note date** field, select a date when the debit note is canceled.

7.  In the **Settlement type** field, select the type of settlement from the following options:
    
      - **None** – No transactions are settled.
    
      - **Open transactions** – Open transactions for the selected debit note are settled in accordance with the First in, First out (FIFO) principle.

8.  Click **Cancel project debit note**.

9.  In the **Post debit note proposals** form, select the **Posting** check box, and then click **OK** to post the debit note. The ledger amounts from the original debit note are posted with a minus sign in the new debit note.

## See also

[(BRA) Post debit note proposal (form)](https://technet.microsoft.com/en-us/library/jj923396\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

