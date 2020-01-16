---
title: About billing rules
TOCTitle: About billing rules
ms:assetid: e90dbf41-0708-4ac4-a0cc-d8a41a1fb610
ms:mtpsurl: https://technet.microsoft.com/library/Hh227474(v=AX.60)
ms:contentKeyID: 36059842
ms.date: 10/15/2014
mtps_version: v=AX.60
f1_keywords:
- project budget
- billing rule
- management fee
- services plus a management fee
- time & material
- time and material
- billing rules
- unit
- unit of delivery
- milestone
- milestone billing
- percentage of completion
- percentage
- unit price
audience: Application User
ms.search.region: Global
---

# About billing rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The topic describes the different types of billing rules that you can set up to complete the invoicing process for a project. When you negotiate a project contract with a customer, you define how and when you can invoice the customer for work on a project. In Microsoft Dynamics AX 2012, after you set up the project contract and the project, you can set up billing rules for the project. When you are ready to invoice the customer, the amount to invoice for the project is calculated based on the billing rules, and a project invoice proposal is generated.

You can set up the following types of billing rules:

  - **Unit of delivery** – Invoice a customer when you complete a unit of delivery. You define the units of delivery in the contract.

  - **Progress** – Invoice a customer when you complete a specified percentage of the project. You can set up a billing rule to automatically calculate the percentage of work completed, or you can manually calculate the percentage of work completed and the amount to invoice the customer.

  - **Milestone** – Invoice a customer for the full amount of a milestone when a project milestone is reached.

  - **Fee** – Invoice a customer for your services plus a management fee, typically a percentage of the cost of services.

  - **Time and material** – Invoice a customer for the value of time and materials used on a project.

## Examples

The following sections provide examples to illustrate how to set up and manage a billing rule for a project.

## Create a billing rule based on the number of units delivered

Your organization offers to provide training to a customer’s employees. Your customer agrees to use your services for a total of five training sessions, at a cost of 10,000 per training session. You invoice the customer at the conclusion of each training session.

Set up the billing rules for the contract with the following values:

  - The unit of delivery is one training session.

  - The unit price is 10,000 per training session.

  - The total number of units is five training sessions.

When you have completed one training session, you can create an invoice for 10,000 for the first unit delivered.

## Create a billing rule based on a specified percentage of project completion, manually calculated

Your organization, a software consulting firm, enters into an agreement with a customer to develop part of a product that the customer is developing. Your organization agrees to deliver the software code over a period of six months. The customer agrees to pay your organization a total of 100,000 for the work. You create a billing rule to invoice the customer based on a percentage of work completed on the project as specified in the contract.

  - At the end of the first month, you meet with the customer to determine the percentage of work completed. Upon review of the project, you and the customer decide that the project is 15 percent completed.

  - You create an invoice in the amount of 15,000 (15 percent of 100,000) and send the invoice to your customer.

## Create a billing rule based on a specified percentage of project completion, automatically calculated

Your organization is a software development firm. You agree to develop a payroll accounting package for a customer for 30,000. The customer agrees to pay your organization based on the percentage of work completed. You estimate that the project costs are 20,000. The project contract specifies the categories of work for you to use in the billing process. You set up billing rules that automatically calculate the invoice amounts for the percentage of work completed for each category. You set up a budget for each category:

  - Development – Cost of 15,000 and revenue of 20,000

  - Installation – Cost of 5,000 and revenue of 10,000

When you create a customer invoice for the first time, the invoice amount is automatically calculated based on the following information:

  - After a month, the worker on the project submits a timesheet for the project. The cost of the worker’s hours is 5,000 for development and 1,000 for installation. The development work is 33 percent complete (5,000 actual cost/15,000 budget cost), and the installation work is 20 percent complete (1,000 actual cost/5,000 budget cost).

  - The invoice amount of 8,667 is automatically calculated (33 percent of 20,000 plus 20 percent of 10,000).

  - You create an invoice in the amount of 8,667 to submit to the customer.

## Create a billing rule based on agreed-upon milestones

Your organization, a management consulting firm, offers your services to conduct market research for a consumer product that the customer plans to sell. The customer agrees to use your services for a period of three months, starting in March, and agrees to pay your organization 50,000. The project has three milestones:

  - Milestone 1: Collect consumer data – March 31

  - Milestone 2: Analyze consumer data – April 30

  - Milestone 3: Present a product viability proposal – May 31

The customer agrees to pay your organization 10,000 for the first milestone, and 20,000 for the second and the third milestones.

When you set up the project contract, you agree to bill the customer based on the completed milestone. The billing rule setup includes the following steps:

1.  Define the project milestones.

2.  Define the amount to invoice the customer at the successful completion of each milestone.

When the first milestone is completed on March 31, mark the milestone as complete and then create an invoice in the amount of 10,000 to submit to the customer. You can’t create an invoice for a milestone until you have marked the milestone as complete.

## Create a billing rule based on services plus a management fee

Your organization, a management consulting firm, offers your services to a retail company. The customer wants your organization to conduct market research to evaluate the viability of a product that is in development. Your organization enters into an agreement with the customer to provide the services of your top three management consultants to conduct the research on a time-and-materials basis. The customer agrees to pay 100 per hour plus a 10 percent management fee for the consulting hours that are charged to the project.

When you set up the project contract, create a billing rule to add a 10 percent management fee to the consulting hours charged to the project.

When you create an invoice for the customer, the customer is billed a 10 percent management fee plus the cost of the consulting hours. For example, if the three consultants worked a total of 200 hours on the project, an invoice is created in the amount of 22,000, by using the following calculation:

  - 200 hours at 100 per hour = 20,000

  - 10 percent management fee = 2,000

  - Total invoice amount = 22,000

If fees are taxable to a customer, and you select a sales tax group in the project contract, the sales tax group is automatically entered in a billing rule for fees.


> [!NOTE]
> <P>Sales tax must be enabled for U.S. taxation rules. For more information about how to set up sales tax, see <A href="https://technet.microsoft.com/library/aa557286(v=ax.60)">General ledger parameters (form)</A>.</P>



## Create a billing rule for the value of time and materials

Your organization offers software consulting services. You have agreed with your customer to provide five technical consultants to work on a software development project for the next six months. The customer agrees to pay 150 for each consulting hour and the cost of office supplies. Your organization sends an invoice to the customer at the end of each month.

When you set up the project contract, you agree to bill the customer monthly for time and materials on the project. You create a billing rule that includes the following information:

  - The contract time period is six months.

  - Consulting time is calculated at a value of 150 per hour.

  - Office supplies are invoiced at cost, not to exceed 10,000 for the project.

  - You create a customer invoice at the end of each calendar month during the project.

During the first month, a total of 800 hours are recorded by the consultants on the project. The cost of office supplies charged to the project is 2,000. At the end of the month, you create an invoice for 122,000, calculated as 800 hours at 150 per hour plus 2,000 for office supplies.

## See also

[Billing rules (form)](https://technet.microsoft.com/library/hh227642\(v=ax.60\))

[Create billing rules](create-billing-rules.md)

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Project budget (form)](https://technet.microsoft.com/library/hh227438\(v=ax.60\))

[About project budgets and forecasts](about-project-budgets-and-forecasts.md)

  


