---
title: Register payments automatically for intercompany customer invoices
TOCTitle: Register payments automatically for intercompany customer invoices
ms:assetid: 64e094d2-c0fb-4741-a653-07aa89c9d31c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571143(v=AX.60)
ms:contentKeyID: 36057725
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- automatic payment
- intercompany invoice
- intercompany payment
- intercompany sales order invoice
- register payment
---

# Register payments automatically for intercompany customer invoices [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX creates a customer transaction when an intercompany customer invoice is posted. This customer transaction remains open until it is settled, which means that it has been paid. When the corresponding intercompany purchase order is invoice updated, a vendor transaction matching the customer transaction is created. This vendor transaction also remains open until it is settled. To reduce the risk of differences, an accounts receivable payment journal can be automatically created and posted when the accounts payable payment journal is posted.

1.  Click **Sales and marketing** \> **Common** \> **Customers** \> **All customers**. On the **Action Pane**, on the **General** tab, click **Intercompany**.

2.  To set up the intercompany accounts receivable payments in the **Intercompany** form for sales orders, click the **Sales order policies** link.

3.  In the **Payment journal** field, select the accounts receivable payment journal that you want to register intercompany vendor payments to. You set this up in the **Accounts receivable parameters** form.

4.  If you want to post to this journal automatically, select the **Post journal automatically** check box.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

