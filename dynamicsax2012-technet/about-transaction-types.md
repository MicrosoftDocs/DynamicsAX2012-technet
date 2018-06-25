---
title: About transaction types
TOCTitle: About transaction types
ms:assetid: 73f4d742-772a-4c86-ac04-725156fbe7bf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550018(v=AX.60)
ms:contentKeyID: 36966729
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- item
- hour
- category group
- fee
- transaction type
- expense
- fee - subscription
---

# About transaction types [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After a project is created, transactions are entered in journals or in project-related forms. These forms can include free text invoices, purchase orders, purchase requisitions, or vendor invoices.

Four predefined transactions types are supported in **Project management and accounting**:

  - **Hour** – Transactions are linked to the financial compensation of project workers, such as consulting, installation, or design.

  - **Expense** – Transactions are associated with a project, unless the transactions are related to items or costs. Examples include travel expenses or vendor services.

  - **Item** – Transactions are linked to items that are purchased for resale, and to items that are consumed in a project, such as when a customer purchases a new computer for the project through the company.

  - **Fee** – Fixed revenues are associated with a Time and material project, such as a bonus for the early delivery of a project blueprint plan and budget.

In addition to these transaction types, on-account transactions represent prepayments for a Time and material project or schedule payments for Fixed-price projects.

All transaction types have the following characteristics:

  - The system searches for default sales and cost prices, and applies them to the transaction. The prices can be overridden in the journal.

  - The sales tax group is taken from the project or project contract. For non-item transactions, the item sales tax is based on the specified project category.

  - The line property for a transaction indicates whether the recorded transaction can be invoiced. Chargeable line properties apply only to Time and material projects.

  - Hour, expense, and fee transactions can be validated by the system. This lets you control how project transactions are recorded, by limiting the values available for workers, projects, and categories in journals and timesheets.

  - Project transactions are usually both summarized by posting to the general ledger, and managed in the project ledger.

## Transaction categories and category groups

In **Project management and accounting**, you can categorize revenue and expenses on projects to control posting to the general ledger, and for detailed reporting and analysis. By categorizing expenses and revenues separately from the general ledger, project managers can get additional details about project performance.

To make it easier for companies to categorize transaction types, categories in Microsoft Dynamics AX are shared between **Production control**, **Travel and expense**, and **Project management and accounting**. To create a new category to use with project transactions, you must first create it as a shared category.

Category groups let you share properties, primarily posting profiles, between related categories. At least one category group must be created for each transaction type, and each project category must be assigned a category group. Because project categories are assigned to a single group, they are associated with the same transaction type as the category group.

When you enter a project category on a transaction line, the category selection is limited to the categories that are set up and linked to this transaction type. For example, when an expense transaction is entered, only expense categories are available.

## Example

You define two category groups, Travel and Hotel. Each category group has two categories. The categories for the Travel category group are Mileage and Airfare. The categories for the Hotel category group are Workday and Weekend.

Both category groups have the transaction type **Expense**. Their categories also have the transaction type **Expense**.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type</p></th>
<th><p>Category group</p></th>
<th><p>Category</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>Travel</p></td>
<td><p>Mileage</p></td>
</tr>
<tr class="even">
<td><p>Expense</p></td>
<td><p>Travel</p></td>
<td><p>Air fare</p></td>
</tr>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>Hotel</p></td>
<td><p>Weekend</p></td>
</tr>
<tr class="even">
<td><p>Expense</p></td>
<td><p>Hotel</p></td>
<td><p>Workday</p></td>
</tr>
</tbody>
</table>


## See also

[Create categories and category groups for projects](create-categories-and-category-groups-for-projects.md)

[Configuring category groups, categories, and cost templates](configuring-category-groups-categories-and-cost-templates.md)

[About project category groups](about-project-category-groups.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

