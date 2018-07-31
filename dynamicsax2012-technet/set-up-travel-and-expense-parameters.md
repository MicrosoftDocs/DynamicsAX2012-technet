---
title: Set up travel and expense parameters
TOCTitle: Set up travel and expense parameters
ms:assetid: 48f3e54f-510a-45dc-8f66-03b95f08f0c0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231400(v=AX.60)
ms:contentKeyID: 36056934
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- expenses
- expense
- travel
audience: Application User
ms.search.region: Global
---

# Set up travel and expense parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you begin to work in **Travel and expense**, you can set default values in the **Travel and expense parameters** form. By presetting these values, you can reduce the amount of data that must be entered manually when you create new expense reports and complete expense report transactions.

1.  Click **Travel and expense** \> **Setup** \> **Travel and expense parameters**.

2.  Add information to the form tabs as described in the following sections.
    
    For detailed information about this form, including individual field descriptions, see [Travel and expense parameters (form)](https://technet.microsoft.com/en-us/library/hh242465\(v=ax.60\)).

## General

On the **General** tab:

  - Set mileage rates for employee travel.

  - Specify how employee personal expenses are paid.

  - Specify whether to apply expense policies to expense reports that are created for a project.

  - Enable line entry for multiple legal entities on an expense report.
    
    This option is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.

## Financial

On the **Financial** tab:

  - Select the ledger journal name for posting expense reports.

  - Select whether to post an expense report immediately to the general ledger upon approval.

  - Define whether to post expense reports to the general ledger or to first create a journal.

  - Select whether to include sales tax on an expense amount that is submitted by an employee.

## Corporate card

On the **Corporate card** tab:

  - Select the default account that must be used for credit card transaction disputes.

  - Add links to your company’s dispute process and to any frequently asked questions regarding the dispute process.

## Per diem

On the **Per diem** tab:

  - Enter the minimum number of hours an employee must work to receive a per diem allowance.

  - Define meal percentage allowances for the first and last days of a per diem transaction schedule. For example, an employee is traveling on those days and does not begin work until noon. If the work day ends at 5 P.M., and your company does not pay for employee travel, you might determine that the employee receives a per diem amount for only five hours of work.

  - Define meal percentage reductions for employees. The meal percentage reduction is the percentage by which a meal allowance is reduced to account for complimentary meals.

## Additional information

On the **Additional information** tab:

  - Define additional header fields to display on an expense report. You can use these header fields to require more information about the expenses incurred by employees.

## Fax cover pages

On the **Fax cover pages** tab:

  - Add instructions to include on fax cover pages.

  - Select the information to include in the bar code.

  - Select the bar code to use on fax cover pages. Click **Organization administration** \> **Setup** \> **Bar codes**.

  - Select whether to include overview information about expense reports on the bar-coded cover page.

## See also

[Project expense policies (form)](https://technet.microsoft.com/en-us/library/hh227585\(v=ax.60\))

  


