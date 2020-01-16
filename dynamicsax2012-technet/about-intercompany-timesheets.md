---
title: About intercompany timesheets
TOCTitle: About intercompany timesheets
ms:assetid: e408e773-827a-410c-8392-0a2368af4f2a
ms:mtpsurl: https://technet.microsoft.com/library/Hh597266(v=AX.60)
ms:contentKeyID: 39519346
ms.date: 10/15/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About intercompany timesheets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Intercompany timesheets make it possible for workers who are employed by one legal entity to enter timesheet hours for work that they do on projects in other legal entities in the same organization. The legal entity that employs a worker is called the loaning legal entity. The legal entity that manages the project for which the worker contributes hours is called the borrowing legal entity.

The following prices are incorporated into intercompany timesheets:

  - A cost price, which the loaning legal entity incurs by using the worker

  - A sales price, which the customer pays the borrowing legal entity

  - A transfer price, which is the amount that the borrowing legal entity pays to the loaning legal entity for the use of its worker

In Microsoft Dynamics AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2, intercompany timesheets for a loaning legal entity are posted to an intercompany cost account. These posts are offset by payroll allocation accounts. In earlier versions of Microsoft Dynamics AX 2012, intercompany timesheets were posted as project costs.


> [!WARNING]
> <P>If you make an adjustment to an intercompany timesheet, the general ledger accounts of the two legal entities that are involved in the adjusted transaction may become out of balance. In this case, you must manually adjust the account balances.</P>



## Setup tasks for intercompany timesheets

Before a worker can create and submit timesheets for work performed in a different legal entity, both the loaning and borrowing legal entities must perform certain setup tasks.

## Setup tasks for the loaning legal entity

The loaning legal entity must perform the following tasks:

  - Enable intercompany timesheet functionality. For information, see [Set up parameters for a timesheet system](set-up-parameters-for-a-timesheet-system.md).

  - Set up a cost price for the worker. This price setup task is performed for all workers, regardless of whether they will be loaned to other legal entities. For information, see [Set up cost prices and sales prices for projects](set-up-cost-prices-and-sales-prices-for-projects.md) and [Cost price - hour (form)](https://technet.microsoft.com/library/aa572459\(v=ax.60\)).

  - Set up a transfer price for the loaned worker. The transfer price is the amount that the loaning legal entity charges the borrowing legal entity. For information, see [Set up transfer prices for intercompany timesheets](set-up-transfer-prices-for-intercompany-timesheets.md).

  - Set up ledger posting profiles for the **Intercompany cost** and **Intercompany revenue** accounts. For information, see [Set up a ledger posting account for projects](set-up-a-ledger-posting-account-for-projects.md) and [Ledger posting setup (form)](https://technet.microsoft.com/library/aa599270\(v=ax.60\)).

  - Specify the debit and credit accounts for each legal entity that workers will be loaned to. For information, see [Set up centralized customer payments](set-up-centralized-customer-payments.md), [Set up centralized vendor payments](set-up-centralized-vendor-payments.md), and [Intercompany accounting (form)](https://technet.microsoft.com/library/aa619468\(v=ax.60\)).

## Setup tasks for the borrowing legal entity

Before a borrowing legal entity can add a borrowed worker to one of its projects, a project manager for the borrowing legal entity must perform the following tasks:

  - Set up sales prices for borrowed workers. This price setup task is performed for all workers, regardless of whether they will be loaned to other legal entities. For intercompany timesheet scenarios, this sales price is the amount that the borrowing legal entity charges the customer for the borrowed worker’s hours. For information, see [Set up cost prices and sales prices for projects](set-up-cost-prices-and-sales-prices-for-projects.md) and [Sales price - hour (form)](https://technet.microsoft.com/library/aa634053\(v=ax.60\)).

  - Specify the debit and credit accounts for each legal entity that workers will be borrowed from. For information, see [Set up centralized customer payments](set-up-centralized-customer-payments.md), [Set up centralized vendor payments](set-up-centralized-vendor-payments.md), and [Intercompany accounting (form)](https://technet.microsoft.com/library/aa619468\(v=ax.60\)).

  - Optional: Add the worker to one or more project validation groups. For information, see [Define validation connections](define-validation-connections.md) and [Set up validation groups](set-up-validation-groups.md).

## Impact on profit and loss accounts in intercompany timesheet scenarios

When a loaned worker posts timesheet hours for work that was completed for a borrowing legal entity, the profit and loss accounts of both legal entities are affected.

**Example**

Contoso–USA is an advertising agency that designs brand logos and commercials for a variety of corporate clients. Sanjay, a graphic designer, is a full-time employee in a subsidiary company, Contoso–India. He is currently loaned to Contoso–USA to design billboards for an upcoming convention for one of its clients, Fabrikam USA. This project is owned and executed by Contoso–USA.

The following table shows the rates that have been set up for this arrangement.


> [!NOTE]
> <P>In this scenario, the cost price and transfer price are normally set up in the currency of the legal entity that employs the worker, which is Indian Rupees in this example. However, for ease of explanation, all rates are shown in US dollars.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Rate type</p></th>
<th><p>Description</p></th>
<th><p>Amount in USD</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Cost price</p></td>
<td><p>The amount per hour that Contoso–India incurs by using Sanjay.</p></td>
<td><p>USD 100.00</p></td>
</tr>
<tr class="even">
<td><p>Transfer price</p></td>
<td><p>The hourly price that the loaning legal entity, Contoso–India, charges the borrowing legal entity, Contoso–USA.</p></td>
<td><p>USD 150.00</p></td>
</tr>
<tr class="odd">
<td><p>Sales price</p></td>
<td><p>The price that the borrowing legal entity, Contoso–USA, charges the customer, Fabrikam USA, for Sanjay’s hourly work</p></td>
<td><p>USD 200.00</p></td>
</tr>
</tbody>
</table>


Sanjay creates a new timesheet, specifies Contoso–USA as the legal entity for a line, and submits 40 hours for the Fabrikam project.

David, the project manager in Contoso–USA, reviews the timesheet line for Sanjay’s work on the Fabrikam project and approves it. The timesheet line is posted and the hours are billed. This affects the P\&L of Contoso–USA and Contoso–India in the following ways:

  - Contoso–USA records a gross profit of USD 2,000.00 from the USD 8,000.00 in revenue that it receives from Fabrikam, minus the USD 6,000.00 that it pays to Contoso–India.

  - Contoso–India records a gross profit of USD 2,000.00 from the USD 6,000.00 in revenue that it receives from Contoso–USA, minus USD 4,000.00 as the cost of services for Sanjay’s work.
    
    In Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, the ledger entry for Contoso–India for the cost of Sanjay’s hours is posted to an intercompany cost account that is offset by a payroll allocation account. By default, the financial dimension from Sanjay’s worker profile is copied to the ledger entries.

## See also

[Preview, update, and manually post approved timesheets](post-timesheet-hours-and-view-distributions.md)

[Create a timesheet](create-a-timesheet.md)

[Review and approve timesheets](review-and-approve-timesheets.md)

[Unposted timesheets (list page)](https://technet.microsoft.com/library/hh597166\(v=ax.60\))

  


