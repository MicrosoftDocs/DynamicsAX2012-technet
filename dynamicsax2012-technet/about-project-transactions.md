---
title: About project transactions
TOCTitle: About project transactions
ms:assetid: b3ddd882-ed40-4c9f-814f-ca41cfc00cde
ms:mtpsurl: https://technet.microsoft.com/library/Hh271626(v=AX.60)
ms:contentKeyID: 36384258
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- expense transaction
- fee transaction
- hour transaction
- item transaction
- on-account transactions
- project transactions
- subscription transaction
- transaction type
audience: Application User
ms.search.region: Global
---

# About project transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, project transactions are grouped by type. Grouping transactions by type makes it easier to post and track project information, such as costs. Transaction types are assigned to category groups. Category groups include categories of the same type. For example, the Travel category group might have a transaction type of Expense, and could include the Mileage and Airfare categories.


> [!NOTE]
> <P>Project transactions are primarily entered in the Microsoft Dynamics AX client. However, timesheets and expenses reports are entered in Enterprise Portal for Microsoft Dynamics AX.</P>



Although in Enterprise Portal you can enter only timesheet hours and expense reports, you can view other transaction types. The following sections describe the transaction types that you can view.

## Hour transactions

Hour transactions are used for costs that are associated with payments made to project workers, typically for time that is spent working on a project.

## Item transactions

Item transactions are used for costs that are associated with the purchase or resale of items for a project, and actual item consumption.

## Expense transactions

Expense transactions are used for costs that are not item or hour transactions, such as project-related travel expenses.

## Fee and fee-subscription transactions

Fee transactions are used for revenues that are related to time and material projects, such as a bonus for meeting a project deadline ahead of schedule. You might have to adjust revenues or add fixed revenues that are not related to actual hour consumption, expenses, or items. For example, if you receive a bonus or rebate, you would use the fee transaction type to adjust revenues.

These transactions are also used for costs that are associated with subscriptions and subscription transactions, and the invoicing and accrual of subscription transactions.

Fee transactions can be created automatically for service subscriptions. Service subscriptions are agreements where customers pay in advance for periodic or regular services. Transactions that are entered as subscription fees, for service subscriptions, are charged to the subscription customers by creating a project invoice.

## On-account transactions

You can also view on-account transactions for projects. On-account invoicing is the standard invoicing method for fixed-price projects, and can also be used for time and material projects.

For fixed-price projects, on-account invoices are primarily used to define milestone billing and prepayments that can be offset when the actual expense is incurred. The on-account amount is entered as one line, and other lines are entered as offset transactions. For example, if you want to set up a billing schedule for a customer for the duration of a project, and display the expenses that are related to the payments on the invoice, you can create an on-account invoice for payments.


> [!NOTE]
> <P>On-account invoicing can be used only for external project types.</P>



## See also

[View project transactions (EP)](view-project-transactions-ep.md)

[Key tasks: Create expense reports](key-tasks-create-expense-reports.md)

  


