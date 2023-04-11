---
title: Create invoice proposals for projects with and without billing rules
TOCTitle: Create invoice proposals for projects with and without billing rules
ms:assetid: caddee24-9551-498e-aef7-1cbbfe9dfc74
ms:mtpsurl: https://technet.microsoft.com/library/Aa572664(v=AX.60)
ms:contentKeyID: 36059335
author: tonyafehr
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project
- invoice proposal
- on-account invoice
- project invoice
- preliminary invoice
- project transaction
audience: Application User
ms.search.region: Global
---

# Create invoice proposals for projects with and without billing rules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you create a customer invoice for a project, you can create a preliminary invoice. This preliminary invoice is also known as an invoice proposal. In the invoice proposal, you define the information about a customer invoice, such as the invoicing method and the transactions that are included.

You can create multiple invoice proposals at the same time by selecting filters to search for project transactions. For example, you can search for all transactions of a specific type, such as all hour transactions. You can also search in a specific date range and select whether to include lines from sales orders. After you review an invoice proposal for the selected types and date range, you can post the invoice proposal.

You can also create invoice proposals for a group of projects that are assigned billing rules. Use filters to select transactions in a specific date range, and specify whether to include sales order lines for the projects.

You can create an invoice proposal for a specific project directly from the project. For more information about how to create an invoice proposal for a specific project, see [Create and post invoice proposals](create-and-post-invoice-proposals.md).

## Create invoice proposals for projects that do not have billing rules

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**. On the **Action Pane**, in the **New** group, click **Invoice proposal**.

2.  In the **Invoicing method** field, select the source of the transactions to include in the invoice proposals:
    
      - **Invoices** – Include transactions that have been posted from journals or other documents, and that are ready to be invoiced.
    
      - **Credit notes** – Include transactions that were originally included on an invoice, but that must now be updated by a credit note.
    
      - **Both** – Include both transaction types in the proposal.

3.  In the **Include transaction type** section, select the types of transactions to include in an invoice proposal.

4.  If you want to include sales order lines in the invoice proposal, select the **Sales order line** check box. Then, in the **Update item quantity** field, select the status of the sales order lines to include in the invoice proposal.

5.  In the **Update item quantity** field, select the status of the sales order lines to include in the invoice proposal.
    

    > [!NOTE]
    > <P>The <STRONG>Update item quantity</STRONG> field is available only if you select the <STRONG>Sales order line</STRONG> check box.</P>



6.  In the **Select transactions** section, specify the date range in which to search for transactions. If you don’t select dates, all unbilled project transactions are displayed in the search results.

7.  In the **Invoice date** field, select the date on which to post the invoice proposal. By default, the current date is displayed.

8.  Click **Search**, and then in the search results, select the transactions to include in an invoice proposal. By default, all transactions are selected.

9.  If a funding source for the selected project has prepaid an amount on the contract price, the amount is displayed in the **Reconciliation with customer advances** section. To include only some of a customer advance in the invoice proposal, click **Split advance amount**. In the **Split customer advance transaction** form, enter the amount of a customer advance to include in the invoice proposal. The amount that you enter is a reduction of the invoice proposal amount.

10. Click **OK**.

11. In the **Invoice proposals** form, click **Post**.

12. In the **Post invoice proposals** form, modify any information as needed, and then click **OK**.

## Create invoice proposals for projects that have billing rules

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**. On the **Action Pane**, in the **New** group, click **Invoice proposal from billing rule**.

2.  In the **Create invoice proposal** form, in the **Project contract** field, select the project contract to create an invoice proposal for.

3.  If you want to include sales order lines in the invoice proposal, select the **Sales order line** check box. Then, in the **Update item quantity** field, select the status of the sales order lines to include in the invoice proposal.
    

    > [!WARNING]
    > <P>The <STRONG>Update item quantity</STRONG> field is available only if you select the <STRONG>Sales order line</STRONG> check box.</P>



4.  In the **Project date** section, specify the date range in which to search for transactions. If you don’t select dates, all unbilled project transactions are displayed in the search results.

5.  In the **Invoice date** field, select the date on which to post the invoice proposal. By default, the current date is displayed.

6.  If a funding source for the selected project has prepaid an amount on the contract price, the amount is displayed in the **Reconciliation with customer advances** section. To include only some of a customer advance in the invoice proposal, click **Split advance amount**. In the **Split customer advance transaction** form, enter the amount of a customer advance to include in the invoice proposal. The amount that you enter is a reduction of the invoice proposal amount.

7.  Click **OK**.

8.  In the **Invoice proposals** form, click **Post**.

9.  In the **Post invoice proposals** form, modify any information as needed, and then click **OK**.

## See also

[Create invoice proposals (class form)](https://technet.microsoft.com/library/aa600958\(v=ax.60\))

[Create invoice proposals for projects that have billing rules (form)](https://technet.microsoft.com/library/jj683235\(v=ax.60\))

[Enter on-account invoice transactions](enter-on-account-invoice-transactions.md)

[Post invoice proposals (form)](https://technet.microsoft.com/library/aa620017\(v=ax.60\))

  


