---
title: Create an intercompany project invoice
TOCTitle: Create an intercompany project invoice
ms:assetid: 73987788-75b0-4484-8da4-1fed94fb73de
ms:mtpsurl: https://technet.microsoft.com/library/Dn528662(v=AX.60)
ms:contentKeyID: 59636747
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- intercompany
- project invoice
- borrowed resource
- Forms.ProjIntercompanyInvoice
- MsDynAx060.Forms.ProjIntercompanyInvoice
- Forms.ProjIntercompanyTransactionSelection
audience: Application User
ms.search.region: Global
---

# Create an intercompany project invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You organization might have multiple divisions, subsidiaries, and other legal entities that transfer items and services to each other for projects. A legal entity may also allow its employees to work on a project for another legal entity. In Microsoft Dynamics AX, the legal entity that provides these resources is called the *lending legal entity* and the legal entity that receives the resources is called the *borrowing legal entity*.

A project accountant in a lending legal entity can create an intercompany customer invoice for the project costs that are being transferred to the borrowing entity. After the intercompany customer invoice is approved and posted, the lending legal entity can send the intercompany invoice to the borrowing legal entity.

The project accountant for the lending legal entity can also set up a batch process to generate intercompany invoices on a recurring basis. The project accountant can select criteria such as transaction types and specific projects to create intercompany invoices in a batch.

## Prerequisites

To set up your organization for intercompany resource transfer, your system administrator must complete the following steps:

1.  Set up vendors, customers, and items for intercompany trade.

2.  Enable intercompany resource scheduling and timesheets in the lending legal entities **Project management and accounting parameters** form.

3.  Define the ledger accounts that are used for posting the intercompany cost of loaned resources and the intercompany revenue received in the **Ledger posting setup** form in the **Project management and accounting** module.

4.  Define transfer pricing between the legal entities in the **Transfer price** form in the **Project management and accounting** module.

## Prerequisites for the lending legal entity

Before the project accountant for the lending legal entity can create an intercompany invoice, the following tasks must be completed.

  - Select options for intercompany transactions:
    
      - Enable intercompany resource scheduling and timesheets.
    
      - Select default values for project categories for intercompany timesheets and expenses. You can select project categories for each borrowing legal entity.
    
      - Specify whether accrued revenue is posted when an intercompany invoice is posted.
    
      - Specify the financial dimensions that are used by default for posting intercompany transactions.
    
    For more information about how to select these options, see [Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\)).

  - Select financial accounts and other posting details for recording intercompany costs and revenue. For more information about how to set up posting details, see [Ledger posting setup (form)](https://technet.microsoft.com/library/aa599270\(v=ax.60\)).

  - Define the transfer price for project costs that are being transferred to the borrowing legal entity. Different prices can be specified for any combination of lending legal entity, borrowing legal entity, project, project contract, and worker. For more information, see [About cost prices, sales prices, and transfer prices in projects](about-cost-prices-sales-prices-and-transfer-prices-in-projects.md).

## Prerequisites for the borrowing entity

Before the project accountant for the borrowing legal entity can post the costs for transferred resources, the following tasks must be completed.

  - Select a category to use by default when recording costs for borrowed resources. For more information about how to select a default category for posting intercompany transactions, see [Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\)).

  - Select financial accounts and other posting details for recording costs for borrowed resources. For more information about how to set up posting details, see [Ledger posting setup (form)](https://technet.microsoft.com/library/aa599270\(v=ax.60\)).

  - Specify the financial dimensions that are used by default for posting intercompany transactions.

## Create an intercompany customer invoice for selected project transactions

Use this procedure to create an intercompany customer invoice for project transactions. Select criteria to search for hours that were posted by workers on projects in borrowing legal entities, and for expenses that were incurred by your legal entity on behalf of borrowing legal entities. You can search by legal entity name, project contract number, project number, date range, or any combination of these options. In the search results, select the transactions to add to an intercompany invoice.

1.  Click **Project management and accounting** \> **Common** \> **Project invoices** \> **Intercompany customer invoices**. On the **Intercompany customer invoices** list page, on the **Action Pane**, click **Intercompany customer invoice**.

2.  In the **Create invoice proposal** form, in the **Legal entity** field, select a borrowing legal entity.

3.  Optional: Enter a specific project contract and project number.

4.  Narrow the search by selecting a date range. Enter specific dates in the **Start date** and **End date** fields. Only intercompany transactions that are posted within this date range are displayed in the search results.

5.  Specify whether to include only hour transactions that were posted by a borrowed resource or both hour and expense transactions in the search. By default, both transaction types are selected.

6.  Click **Search**.

7.  In the search results, select the transactions to include in an intercompany invoice proposal, and then click **OK**.

8.  In the **Intercompany customer invoice** form, on the **Action Pane**, click the **Line view** button. On the **Invoice lines** FastTab, the intercompany project transactions that you selected from the search results are displayed. To modify the transactions before you send the invoice to the borrowing legal entity, do the following:
    
      - Open the **Create invoice proposal** form and select additional intercompany transactions for the current invoice, click **Add line**.
    
      - Delete a line, by selecting it, and then click **Remove**.
    
      - Change the description, category, quantity, unit price, and indirect costs for a line as needed.
    
      - View comments, reasons, financial dimensions, and other information about a selected line on the tabs on the **Invoice lines** FastTab.

9.  To post the intercompany customer invoice, on the **Action Pane**, click **Post**.
    

    > [!NOTE]
    > <P>If your organization requires that intercompany invoices be reviewed before they are posted, a system administrator might set up a workflow for intercompany invoices. If a workflow is not set up for intercompany invoices, you can post the intercompany invoice.</P>



## Create a batch job for intercompany invoices

You can create multiple intercompany invoices at the same time by selecting filters to search for intercompany transactions for all borrowing legal entities. For example, you can search for projects that are managed by other legal entities for all hour transactions that are posted by borrowed workers, and then create an intercompany invoice for each borrowing legal entity for the transactions that are displayed in the search results.

1.  Click **Project management and accounting** \> **Periodic** \> **Project invoices** \> **Create intercompany customer invoices**.

2.  In the **Create intercompany customer invoices** form, in the **Company** field, select a legal entity to invoice. If you don’t select a company, all transactions that meet the search criteria are displayed for all borrowing legal entities.

3.  In the **Create one invoice per** field, select whether to create an invoice for intercompany transactions based on a project or based on a borrowing legal entity.

4.  In the **Include transaction type** field group, select whether to search for only hour or expense intercompany transactions. By default, both transaction types are selected.

5.  Optional: To select a specific project and project contract for which to create intercompany invoices, click **Select**. In the **Inquiry** form, in the **Criteria** field, select the project contract, project number, or both, and then click **OK**.

6.  On the **Batch** tab, set up a batch process to create intercompany invoices on a recurring basis. For more information, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

7.  To post the intercompany invoices, on the **Action Pane**, click **Post**.
    

    > [!NOTE]
    > <P>If your organization requires that intercompany invoices be reviewed before they are posted, a system administrator might set up a workflow for intercompany invoices. If a workflow is not set up for intercompany invoices, you can post the intercompany invoices.</P>



## See also

[About intercompany expenses](about-intercompany-expenses.md)

[About intercompany timesheets](about-intercompany-timesheets.md)

[Set up transfer prices for intercompany timesheets](set-up-transfer-prices-for-intercompany-timesheets.md)

  


