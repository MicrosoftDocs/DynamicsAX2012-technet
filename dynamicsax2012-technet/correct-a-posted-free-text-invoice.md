---
title: Correct a posted free text invoice
TOCTitle: Correct a posted free text invoice
ms:assetid: 5df615e5-dcba-4ad1-8b0e-a7f604c18239
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209125(v=AX.60)
ms:contentKeyID: 36057578
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- change posted invoice
- correct posted invoice
- edit posted invoice
- free text invoice correction
- invoice correction
---

# Correct a posted free text invoice [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to correct a free text invoice that has been posted. When you correct an invoice that has been posted, a corrected invoice is created where you can modify the invoice and post it with the new values. When you post the corrected invoice, a canceling invoice is created, which brings the combined balance of the original invoice and the canceling invoice to a zero amount.

For example, if you correct an original posted invoice that has a balance of 500.00, a corrected invoice will be created that has a balance of 500.00. You can change the information for the invoice, and then post it. When the corrected invoice is posted, a canceling invoice will be created that has a balance of -500.00. This brings the combined balance of the original and canceling invoices to 0.00.


> [!NOTE]
> <P>This feature is available only if the <STRONG>Free text invoice correction</STRONG> configuration key is selected. (ESP) To comply with local legal requirements, this feature is available only to legal entities whose primary address is in any country/region except Spain. Use the Spanish correction feature, instead.</P>



1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select a posted invoice.

3.  On the **Action Pane**, click **Correct invoice**, and then enter the following information:
    
      - **Reason code** – Enter or select the reason code that describes why the invoice is being corrected.
    
      - **Comments** – Enter any additional comments about the invoice cancellation.
    
      - **Canceling invoice date** – Enter or select the invoice date to assign to the canceling invoice.

4.  Click **Create corrected invoice**. A corrected invoice is created.

5.  Click **Edit** and make any necessary changes to the invoice.

6.  If required by your organization, submit the corrected invoice for workflow review. When the corrected invoice has been approved, continue to the next step.

7.  In the **Free text invoice** form, on the **Action Pane**, click **Post** and then click **OK**. The corrected invoice is posted, and a canceling invoice is automatically created.

8.  Optional: In the **Free text invoice** list page in the **Cancel** group, click **View**, and then click **Invoice corrections** to view the invoice correction details. These details include the related invoices:
    
      - **Original invoice** – The invoice that includes the information that you are correcting.
    
      - **Corrected invoice** – The invoice that contains the corrected invoice information.
    
      - **Canceling invoice** – The system-generated credit invoice that was created to cancel the invoice that was most recently corrected. This invoice is created when the corrected invoice is posted.


> [!TIP]
> <P>A <STRONG>Correction</STRONG> column is displayed on the <STRONG>All free text invoices</STRONG> list page so that you can easily identify which invoices have been canceled and corrected.</P>



## See also

[Free text invoice (form)](https://technet.microsoft.com/en-us/library/aa556897\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

