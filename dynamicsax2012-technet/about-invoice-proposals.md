---
title: About invoice proposals
TOCTitle: About invoice proposals
ms:assetid: a0f5cfd4-ff8a-47a9-9b9d-47010ba8178c
ms:mtpsurl: https://technet.microsoft.com/library/Aa571807(v=AX.60)
ms:contentKeyID: 36058771
author: Khairunj
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project
- billing rule
- customer invoice
- invoice proposal
- on-account invoice
- credit note
- preliminary invoice
- pro forma invoice
- project transaction
audience: Application User
ms.search.region: Global
---

# About invoice proposals 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you create a customer invoice for a project, you can create a preliminary invoice, or invoice proposal. In an invoice proposal, you can select project transactions to include in a project invoice, and then review the invoice details before you post and send the project invoice to the customer or other funding source.

**Creating invoice proposals**

You can create invoice proposals by manually selecting from a list of transactions for a specified project. You can also set up billing rules that specify when to automatically create an invoice proposal. For example, you can create a billing rule to create an invoice proposal when work on a project is 25 percent, 50 percent, 75 percent, and 100 percent completed.

Invoice proposals can be created for the following transactions:

  - Hours, expenses, and other project transactions.

  - Amounts that are withheld by customers on prior project invoices.

  - Credit notes.

  - Amounts that are paid to you by a customer before a project is started.

  - In Microsoft Dynamics AX 2012 R3, you can create fee transactions in an invoice proposal. You can also modify the sales price on hour, expense, item, and fee transactions. When you post an invoice proposal, the updated prices and transactions are added to project reports and transaction history.

If you want to create multiple customer invoices for a project, you must create an invoice proposal for each invoice. For example, you can create invoices based on transaction type. If you want to specify hours on one customer invoice and items on another, you must create an invoice proposal for hour transactions and a separate invoice proposal for fee transactions.

If a project has more than one funding source, you can create an individual invoice proposal for each funding source. In the **Funding rule allocations** form, you can define the percentage of the transaction amount that you want to allocate to each funding source. For more information about how to create funding rules, see [Funding rule allocations (class form)](https://technet.microsoft.com/library/hh209480\(v=ax.60\)).

**Creating customer invoices from invoice proposals**

After you create and post an invoice proposal, a customer invoice is automatically created for the transactions that are included in the invoice proposal.

You can add or delete transactions in an invoice proposal before you post it. For example, you can remove expense transactions that were posted to a project but are not chargeable to the customer.


> [!NOTE]
> <P>If your organization requires that invoice proposals be reviewed before they are posted, the invoice proposal may need to be approved via a workflow before it is posted.</P>



## See also

[Create invoice proposals (class form)](https://technet.microsoft.com/library/aa600958\(v=ax.60\))

[Invoice proposals (form)](https://technet.microsoft.com/library/aa615408\(v=ax.60\))

[Funding rule allocations (class form)](https://technet.microsoft.com/library/hh209480\(v=ax.60\))

[Invoicing](invoicing.md)

[Create invoice proposals for projects with and without billing rules](create-invoice-proposals-for-projects-with-and-without-billing-rules.md)

[Create and post invoice proposals](create-and-post-invoice-proposals.md)

[Approve or reject an invoice proposal](approve-or-reject-an-invoice-proposal.md)

  


