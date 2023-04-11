---
title: Create an invoice for a time and material project
TOCTitle: Create an invoice for a time and material project
ms:assetid: 3257c81d-17ba-4ef9-a927-2beac5269fae
ms:mtpsurl: https://technet.microsoft.com/library/Aa570061(v=AX.60)
ms:contentKeyID: 36056356
author: tonyafehr
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- invoice
- time and material
- invoice proposal
- project invoice
audience: Application User
ms.search.region: Global
---

# Create an invoice for a time and material project 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Create an invoice proposal for selected transactions for a Time and material project. After the invoice proposal is reviewed and posted, you can create a project invoice to send to the customer.

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Project invoice proposals**. On the **Invoice proposals** list page, on the **Action Pane**, click **Invoice proposal**. If billing rules are assigned to the project, click **Invoice proposal from billing rule**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select or open the Time and material project for which to create an invoice. On the **Action Pane**, on the **Manage** tab, in the **New** group, click **Invoice proposal**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Select or open the project contract for which to create an invoice. On the **Action Pane**, on the **Maintain** tab, in the **New** group, click **Invoice proposal**.

2.  In the **Create invoice proposal** form, in the **Select transactions** section, enter the search criteria for transactions to include in the invoice proposal, and then click **Search**.

3.  In the search results, select the transactions to include in the invoice proposal, and then click **OK**.
    

    > [!NOTE]
    > <P>Transactions from both the projects and subprojects that are attached to the selected project contract are included in the search results.</P>



4.  In the **Invoice proposals** form, examine the contents of the invoice proposal and the transactions that are included in the proposal.
    
    If the information requires an adjustment, delete the line from the proposal, and adjust the transaction. Alternatively, depending on the number of adjustments that you have to make, you can cancel the invoice proposal, adjust the project transactions, and then create the invoice proposal again.

5.  Click **Post** to post the invoice proposal and create the project invoice.
    

    > [!NOTE]
    > <P>If your organization requires that invoice proposals be reviewed before they are posted, a system administrator might set up a workflow for invoice proposals. If a workflow is not set up for invoice proposals, you can post the invoice proposal.</P>



6.  You can invoice a single invoice proposal or select an interval of invoice proposals. To specify the parameters for selecting multiple invoices, click **Select** in the **Post invoice proposals** form.

You can also print an invoice from the **Invoice proposals** form.

## See also

[Approve or reject an invoice proposal](approve-or-reject-an-invoice-proposal.md)

[Invoice proposals (form)](https://technet.microsoft.com/library/aa615408\(v=ax.60\))

[Create invoice proposals (class form)](https://technet.microsoft.com/library/aa600958\(v=ax.60\))

[About on-account invoicing](about-on-account-invoicing.md)

[Post invoice proposals (form)](https://technet.microsoft.com/library/aa620017\(v=ax.60\))

[Adjust transactions](adjust-transactions.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

  


