---
title: (POL) Post a Single Administrative Document (SAD) from the SAD
TOCTitle: (POL) Post a Single Administrative Document (SAD) from the SAD
ms:assetid: eab6ef13-d39d-4e0f-a27b-c10b79733236
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ731084(v=AX.60)
ms:contentKeyID: 49675324
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Post a Single Administrative Document (SAD) from the SAD [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create a Single Administrative Document (SAD) that has associated purchase orders, and how to post the purchases from the SAD.

Before you start working with SADs, you must verify the setup of number sequences, main accounts for SADs, and duty rates groups. For more information, see [(POL) Set up parameters for a Single Administrative Document (SAD)](pol-set-up-parameters-for-a-single-administrative-document-sad.md).

1.  Click **Accounts payable** \> **Common** \> **SAD** \> **SAD documents**.

2.  Click **New** to create a SAD.

3.  In the **Document code** field, enter the code for the SAD, and then complete the remaining fields on the **SAD documents** FastTab. For information about the fields on this FastTab, see [(POL) SAD documents (form)](https://technet.microsoft.com/en-us/library/jj678156\(v=ax.60\)).

4.  On the **SAD document references** FastTab, on the **Positions of SAD** tab, in the **Position** field, enter the line number of the document.

5.  Complete the remaining fields on the **Positions of SAD** tab. For information about the fields on this tab, see [(POL) Create SAD documents (form)](https://technet.microsoft.com/en-us/library/jj731083\(v=ax.60\)).

6.  On the **Invoices for SAD - ledger** tab, in the **Position** field, enter the line number of the invoice.

7.  Complete the remaining fields on the **Invoices for SAD - ledger** tab. For information about the fields on this tab, see [(POL) Create SAD documents (form)](https://technet.microsoft.com/en-us/library/jj731083\(v=ax.60\)).

8.  Click **Purchases** to open the **Purchases for SAD** form, where you can assign purchase orders to the SAD.

9.  In the **Purchase order** field, select a purchase order. Information about the purchase order is displayed, such as the vendor account, purchase type, order status, and currency. Purchase order lines are displayed in the lower pane of the form. The position in the SAD and the invoice line number are based on the settings on the **Positions of SAD** and **Invoices for SAD - ledger** tabs in the **Create SAD documents** form.

10. In the **Currency** field, verify the currency code for the purchase order. The currency code for the purchase order and the SAD must be the same.

11. Close the **Purchases for SAD** form.

12. In the **Create SAD documents** form, click **Post** to post the SAD and the attached purchases. The invoice is generated, and costs for payments, transport, and insurance that are assigned to the invoice are posted to the vendor accounts using the currency of the document.

## See also

[(POL) Set up parameters for a Single Administrative Document (SAD)](pol-set-up-parameters-for-a-single-administrative-document-sad.md)

[(POL) Post a Single Administrative Document (SAD) from the general journal](pol-post-a-single-administrative-document-sad-from-the-general-journal.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

