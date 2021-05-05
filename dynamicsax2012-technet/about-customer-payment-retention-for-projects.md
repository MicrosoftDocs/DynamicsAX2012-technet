---
title: About customer payment retention for projects
TOCTitle: About customer payment retention for projects
ms:assetid: 88863106-9cb8-49ff-9031-e99f319b8f5a
ms:mtpsurl: https://technet.microsoft.com/library/Hh209338(v=AX.60)
ms:contentKeyID: 36058448
author: Khairunj
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- retention
- retention percentage
- customer payment retention
- retention terms
- retention amount
- customer retention
audience: Application User
ms.search.region: Global
---

# About customer payment retention for projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When your organization is working on a project for a customer, the customer may want to withhold payment for part of an invoice until certain terms are met. The customer may retain amounts until the project is completed, or until the project reaches a specified stage of completion. The payment that the customer withholds is called the *customer retention*. The terms of the customer retention are typically expressed as either a specific amount or as a percentage of a contract or invoice amount.

The terms of the customer retention are described in the project contract. When you set up the retention terms for a customer, you can enter a percentage or you can enter a specific amount for the retention. The retention amount for a customer invoice is automatically calculated and subtracted from the invoice amount based on the retention information that you define.

You can set up any of the following retention terms for a customer:

  - A percentage of each invoice is retained until the project is completed.

  - A percentage of each invoice is retained until the project reaches a specified percentage of completion.

  - An amount is retained from each invoice until the project is completed.

  - An amount is retained from each invoice until the project reaches a specified percentage of completion.

After the project reaches a specified percentage of completion and the customer is satisfied with the status of the project, the customer releases the retained amount. You create a customer invoice for the retained amount.

**Example: Retention until 100 percent complete**

The following example shows how a percentage of the invoice amount is retained for a project until the project is completed.

Your organization creates a project to provide consulting services to install software for a customer. The customer agrees to use your services for four months and agrees to pay USD 100 for each hour of consulting services. The total amount of the project is USD 80,000.

The customer decides to retain 10 percent of the invoice value from each invoice until the project is completed. You set up these retention terms in the project contract in Microsoft Dynamics AX. When a customer invoice is generated, 10 percent of the invoice amount is automatically retained. After the project is completed, the customer reviews the work. The customer approves the work and releases the retained amount.

During the first month, a total of 200 worker hours are added to the project. The invoice that you create for the customer for the month includes the following information:

  - The total amount due for the worker hours is 20,000.

  - The retention amount is calculated as 10 percent of the invoice, or 2,000.

  - The net invoice amount is 18,000.

After the project is completed, you discuss the results of the project with the customer. The customer agrees that the work was completed successfully. You create an invoice for 8,000 (80,000 \* 10 percent).

**Example: Retention until partially complete**

The following example shows how a percentage of the invoice amount is retained for a project until the project has reached a specified percentage of completion.

Your organization agrees to design an office building for a customer. The customer agrees to pay USD 100,000 for the project. The customer decides to retain 10 percent of the amount from each invoice until the project is 50 percent completed. When you create a customer invoice, the retained amount is automatically calculated and subtracted from the total invoice amount.

At the end of the first month, a total of 250 worker hours are recorded on the project. You and the customer inspect the construction work and agree that 20 percent of the work on the project is completed. The invoice that you prepare for the customer includes the following information:

  - The total amount charged for the work hours is 20,000 (100,000 \* 20 percent).

  - The retention amount is calculated as 10 percent of the invoice, or 2,000.

  - The net invoice amount is 18,000.

After you determine that the project is 50 percent completed, you discuss the status of the project with the customer. The customer agrees that 50 percent of the project is complete and releases the retention. You create an invoice for the percentage completed in the current month plus the amount that was retained. The total amount of the invoice is 32,000 (100,000 \* 30% + 2,000).

## See also

[Key tasks: Manage customer payment retention for projects](key-tasks-manage-customer-payment-retention-for-projects.md)

[Customer payment retention terms (form)](https://technet.microsoft.com/library/hh208591\(v=ax.60\))

[Inquire customer retained payments (form)](https://technet.microsoft.com/library/hh209406\(v=ax.60\))

[Request for customer retained amount (form)](https://technet.microsoft.com/library/hh209691\(v=ax.60\))

[Invoice proposals (form)](https://technet.microsoft.com/library/aa615408\(v=ax.60\))

  


