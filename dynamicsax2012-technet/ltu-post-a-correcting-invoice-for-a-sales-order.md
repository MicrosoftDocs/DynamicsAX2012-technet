---
title: (LTU) Post a correcting invoice for a sales order
TOCTitle: (LTU) Post a correcting invoice for a sales order
ms:assetid: 7fd912e4-8473-4d4c-ae4e-845c1f3676cd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665130(v=AX.60)
ms:contentKeyID: 49386711
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LTU) Post a correcting invoice for a sales order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If you post a correction for a posted sales order, the status of the correcting invoice is shown as **Broken** and the status of the incorrect invoice is shown as **Canceled**. The status of the invoice determines which invoice is included in the Invoice registration journal.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the sales order to be corrected.
    

    > [!NOTE]
    > <P>The <STRONG>Status</STRONG> of the sales order must be <STRONG>Open</STRONG>.</P>



3.  Create a new order line in the lower pane, and then click **Invoice** \> **Invoice**.

4.  In the **Documents to update** field, select the number of the invoice that is corrected, and then click **OK** to post the correcting invoice.
    

    > [!NOTE]
    > <P>To select several invoices in the <STRONG>Documents to update</STRONG> field, select the numbers, separated by commas.</P>



## See also

[(LTU) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj678097\(v=ax.60\))

[(LTU) View and manually change the status of invoice document author for a sales order](ltu-view-and-manually-change-the-status-of-invoice-document-author-for-a-sales-order.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

