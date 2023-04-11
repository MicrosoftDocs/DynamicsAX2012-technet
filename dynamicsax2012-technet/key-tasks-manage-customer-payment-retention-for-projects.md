---
title: 'Key tasks: Manage customer payment retention for projects'
TOCTitle: 'Key tasks: Manage customer payment retention for projects'
ms:assetid: f25015ab-14b9-4a9a-9836-cc0d38980896
ms:mtpsurl: https://technet.microsoft.com/library/Hh351824(v=AX.60)
ms:contentKeyID: 36676419
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- retention
- project add-in
- retention percentage
- customer payments
- retention terms
- customer retention
- project contracts
- customer retention terms
- invoice proposals
- partial payments
- payment retention
- retention summary
audience: Application User
ms.search.region: Global
---

# Key tasks: Manage customer payment retention for projects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A project customer might want to withhold or retain an amount from payment to your organization for a project invoice. In Microsoft Dynamics AX, the customer payment retention terms are defined in the project contract. The payment retention terms include the criteria for releasing a retention amount. You can define the payment retention terms as a specific amount or as a percentage of the value of a contract. You can also define the retention amount as a percentage of an invoice amount.

When you set up the payment retention terms for a customer, you enter a percentage or amount in the project contract with the customer. The retention amount for a project invoice is calculated automatically, based on the retention percentage. The retained amount is automatically subtracted from the invoice amount. When the project has reached a specified level of completion, and the customer approves the work, you create an invoice for the retained amount. No retained amount is retained from subsequent invoices on the project.

## What do you want to do?

Learn more about...

Prerequisites

Set up customer payment retention terms

Add customer retention terms to a project contract

Update the percentage of work completed for the project

Verify the amount of customer retention

Create an invoice proposal for the retention amount

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About customer payment retention for projects](about-customer-payment-retention-for-projects.md)

## Prerequisites

Before you can set up payment retention terms for a project, you must complete the following tasks:

  - Set up a general ledger account for posting customer payment retention amounts. For more information, [Accounts for automatic transactions (form)](https://technet.microsoft.com/library/aa548973\(v=ax.60\)).

  - Define a project category for customer payment retention transactions. This category must have a **Fee** category type. For more information, see [Project categories (form)](https://technet.microsoft.com/library/aa582118\(v=ax.60\)).

  - Set up a number sequence for customer payment retention terms. A document number is automatically assigned when you create new customer payment retention terms. For more information, see [Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\)).

Back to top

## Set up customer payment retention terms

When you set up payment retention terms for a customer, you specify the percentage of customer invoices to retain. You can also enter a percentage of completion for retention on the project. Amounts are automatically retained on project invoices for the customer until the project reaches the specified percentage of completion.

1.  Click **Project management and accounting** \> **Setup** \> **Retention** \> **Customer payment retention terms**.

2.  In the **Customer payment retention terms** form, click **New**.

3.  In the **Description** field, enter a descriptive name for the retention term.

4.  In the **Schedule** section, click **Add line**.

5.  In the **Percentage of work complete** field, enter a percentage of completion for the project. Amounts are automatically retained on project invoices until the project stage reaches this percentage. For example, if you enter 50 percent, amounts are retained until the project is 50 percent completed.

6.  In the **Customer payment retention percentage** field, enter the percentage of the invoice amount to retain until the specified percentage of work is completed.

Back to top

## Add customer retention terms to a project contract

When you create a project contract, you can set up the customer payment retention terms. When you create a project and associate it with the project contract, the retention terms that you specify in the project contract are displayed on the **Payment retention terms** FastTab in the **Projects** form.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. Open a project contract in the list, or create a new project contract.

2.  In the **New project contract** form, enter the project contract information, such as the contract ID, funding type, and sales currency. When you click **OK**, this information is added to the project contract header.

3.  In the **Project contracts** form, on the **Funding sources** FastTab, add information about the funding sources, language, and invoice format for each funding source.
    

    > [!IMPORTANT]
    > <P>Customer retention terms can only apply to a funding source of <STRONG>Customer</STRONG>.</P>



4.  In the **Customer payment retention terms** field, select the customer payment retention terms for the selected funding source.

Back to top

## Update the percentage of work completed for the project

When work on the project reaches the percentage of completion that is specified in the retention terms, you can create an invoice for the project. The retention amount is automatically subtracted from the invoice amount.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project from the projects list page.

2.  In the **Projects** form, on the **Action Pane**, click **Edit**.

3.  On the **General** FastTab, in the **Percentage of work complete** field, enter the percentage of work that is completed on the project to date.
    
    The percentage of work completed is automatically compared with the payment retention terms. If the percentage of work that is completed on the project is less than the percentage of completion specified in the payment retention terms, a payment retention amount is calculated and subtracted from invoices that you create for the project.

Back to top

## Verify the amount of customer retention

As work is completed on projects, you can view the status of payment retention amounts by project, by billing rule, by customer, and by invoice.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open the project from the projects list page.

2.  In the **Projects** form, on the **Action Pane**, on the **Control** tab, in the **Retention** group, click **Customer retained payments**.

3.  In the **Inquire customer retained payments** form, on the **Customer payment retention summary** FastTab, review the amounts in the **Total retained amount**, **Total retained amount invoiced**, and **Remaining retained amount** fields for the project.

4.  On the **Funding sources** FastTab, you can review the retained amounts by customer funding source for projects that are funded by multiple sources.

5.  On the **Invoices** FastTab, review the retained amounts for each invoice.

Back to top

## Create an invoice proposal for the retention amount

When a project is completed or reaches the percentage of completion specified in the project contract, create an invoice proposal to request payment by the customer of the retained amount.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open the project from the projects list page.

2.  In the **Projects** form, on the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **Request retained amount**.

3.  In the **Request for customer retained amount** form, on the **Project invoices** FastTab, select the invoice for which to create an invoice proposal, and then, on the menu bar, click **Create invoice proposal**.

4.  In the **Invoice proposals** form, review the value in the **Retention release amount** field, and then post the invoice proposal.
    
    If your organization uses workflow, submit the invoice proposal to workflow for approval.

Back to top

## Find form help

[Customer payment retention terms (form)](https://technet.microsoft.com/library/hh208591\(v=ax.60\))

[Inquire customer retained payments (form)](https://technet.microsoft.com/library/hh209406\(v=ax.60\))

[Request for customer retained amount (form)](https://technet.microsoft.com/library/hh209691\(v=ax.60\))

[Invoice proposals (form)](https://technet.microsoft.com/library/aa615408\(v=ax.60\))

## Find related tasks

[Key tasks: Manage vendor payment retention for projects](key-tasks-manage-vendor-payment-retention-for-projects.md)

  


