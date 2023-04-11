---
title: About on-account invoicing
TOCTitle: About on-account invoicing
ms:assetid: 726a7149-f1f9-42a9-91ca-b03ff7740033
ms:mtpsurl: https://technet.microsoft.com/library/Aa549984(v=AX.60)
ms:contentKeyID: 42517327
author: tonyafehr
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project
- projects
- on-account
- time and material
- fixed-price
- invoice proposal
- on-account invoice
- project invoice
audience: Application User
ms.search.region: Global
---

# About on-account invoicing 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes invoicing for on-account transactions for projects. The amount that you enter in an on-account invoice for a project is based on the timing, percentage of completion, and other billing conditions that are specified in the related project contract. The amount is not calculated based on the hours, items, expenses, or fees that are posted to a project.

On-account invoicing works differently depending on whether you are using Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 R3:

  - In AX 2012, you can create a customer invoice for both Time and material projects and Fixed-price projects by using an on-account invoice. You can create an on-account invoice as a progress billing that is unrelated to specific costs on Time and material projects. You can also create on-account invoices for a specified percentage of Fixed-price contract amounts.

  - In AX 2012 R3, you must first create an on-account transaction for a Time and materials project or a Fixed-price project before you can add the on-account transaction to a project invoice. In the on-account transaction, enter the amount to invoice a customer. To create a project invoice for the amount, create a preliminary invoice, or *invoice proposal*. In an invoice proposal, select the on-account transaction. You can review the on-account information in the invoice proposal before you create a project invoice for it. For more information about how to create an invoice proposal, see [Create and post invoice proposals](create-and-post-invoice-proposals.md).

## Fixed-price projects

For Fixed-price projects, on-account transactions are based on an agreed-upon milestone, unit of delivery, or progress billing arrangement that is specified in a project contract. One line is created for each payment that is to be received from the project customer. No deductions are needed.

## Time and material projects

For Time and material projects, you can bill a customer or other funding source for a prepayment amount by using an on-account invoice proposal. Enter on-account transactions as one line. Optionally, you can enter additional lines as deductions to offset any prepayments that the customer has already made. You can create deduction lines by entering an amount preceded by a minus sign.

## See also

[Enter on-account invoice transactions](enter-on-account-invoice-transactions.md)

[Create invoice proposals for projects with and without billing rules](create-invoice-proposals-for-projects-with-and-without-billing-rules.md)

[Create an invoice for a time and material project](create-an-invoice-for-a-time-and-material-project.md)

[About invoicing fixed-price projects](about-invoicing-fixed-price-projects.md)

[Create an invoice for on-account transactions](create-an-invoice-for-on-account-transactions.md)

  


