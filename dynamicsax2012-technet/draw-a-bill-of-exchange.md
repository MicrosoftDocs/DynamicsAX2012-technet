---
title: Draw a bill of exchange
TOCTitle: Draw a bill of exchange
ms:assetid: 7131006e-ae43-4284-9608-4d452605b12f
ms:mtpsurl: https://technet.microsoft.com/library/Aa571313(v=AX.60)
ms:contentKeyID: 36655932
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Draw a bill of exchange 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can draw a bill of exchange automatically or in a draw bill of exchange journal. A bill of exchange always is based on an open customer transaction, either a customer invoice for a sales order or a free text invoice.


> [!NOTE]
> <P>When you transfer transactions to a journal, the way that due dates are handled depends on how you select the transactions. Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Journals</STRONG> &gt; <STRONG>Payments</STRONG> &gt; <STRONG>Payment journal</STRONG>. Click <STRONG>Lines</STRONG>. You can click <STRONG>Payment proposal</STRONG> &gt; <STRONG>Create payment proposal</STRONG> to select transactions by using a query to select the total number of payments that are due as of a specific date. If you select transactions by using a payment proposal, the date that you enter in the <STRONG>Total payment date</STRONG> field is used for all transferred transactions. If you select transactions manually in the <STRONG>Settle open transactions</STRONG> form, the latest due date of the selected transactions is used.</P>



## Draw a bill of exchange automatically

You can draw a bill of exchange automatically when you post or update a sales order invoice or a free text invoice.

To automatically draw bills of exchange for a method of payment, select the **Create and post draw journal automatically when posting invoices** check box in the **Methods of payment - customers** form. For more information, see [Methods of payment - customers (form)](https://technet.microsoft.com/library/aa499398\(v=ax.60\)).

## Draw a bill of exchange in a journal

You can draw a bill of exchange manually in a draw bill of exchange journal.

To manually draw bills of exchange for a method of payment, clear the **Create and post draw journal automatically when posting invoices** check box in the **Methods of payment - customers** form.

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Draw bill of exchange journal**.

2.  Create a journal, and then click **Lines**.

3.  Select a customer account, and then click **Functions** \> **Settlement** to open the **Settle open transactions** form.

4.  Select the **Mark** check box for an open transaction.

5.  Close the **Settle open transactions** form.

6.  Click **Post** \> **Post**.
    
    The bill of exchange, and a related line that has a status of **Drawn** and a sequence number of 1 or greater, is shown in the **Bill of exchange journal** inquiry form. The bill of exchange also appears in the **Bills of exchange statistics** form.
    
    When the journal is posted, the Bill of exchange account is debited and the Customer summary account is credited in the general ledger.
    

    > [!NOTE]
    > <P>If you cannot post and you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[Remit a bill of exchange](remit-a-bill-of-exchange.md)

[Settle a bill of exchange](settle-a-bill-of-exchange.md)

[Protest a bill of exchange](protest-a-bill-of-exchange.md)

[Redraw a bill of exchange](redraw-a-bill-of-exchange.md)

[Set up bills of exchange](set-up-bills-of-exchange.md)

[Journal voucher - Bill of exchange journal (form)](https://technet.microsoft.com/library/aa553272\(v=ax.60\))

[Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\))

[Place an Accounts receivable transaction on hold](place-an-accounts-receivable-transaction-on-hold.md)

[Select invoices to settle with payments on behalf of multiple legal entities](select-invoices-to-settle-with-payments-on-behalf-of-multiple-legal-entities.md)

  


