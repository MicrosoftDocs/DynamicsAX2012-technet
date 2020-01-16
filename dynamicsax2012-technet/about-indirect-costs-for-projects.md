---
title: About indirect costs for projects
TOCTitle: About indirect costs for projects
ms:assetid: 42172540-49e0-4067-89de-b55131b68579
ms:mtpsurl: https://technet.microsoft.com/library/Hh242374(v=AX.60)
ms:contentKeyID: 36056867
author: Khairunj
ms.date: 10/15/2014
mtps_version: v=AX.60
f1_keywords:
- project add-in
- compounding
- compounding rules
- indirect cost component
- indirect costs
- project indirect costs
audience: Application User
ms.search.region: Global
---

# About indirect costs for projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Your organization might want to include indirect costs to calculate the full cost of a project. Indirect costs may include rent, office supplies, telephone charges, and computer support. You can assign indirect costs to a project and set up the method for calculating the amount of indirect costs to allocate to a project.

Indirect costs are calculated and automatically added to projects by using the following methods:

  - **An indirect cost without compounding rules** – Indirect costs are calculated by using a percentage of a worker’s hourly rate or by using a specific amount per hour posted to a project.

  - **Multiple indirect costs without compounding rules** – Indirect costs are calculated by using a percentage of the sum of (hourly rate + indirect cost A + indirect cost B).

  - **Multiple indirect costs with compounding rules** – The project is charged a percentage of the sum of (hourly rate + indirect cost A + indirect cost B) + ((A+B) × compounding percent).

## Examples

These examples describe some of the ways that you can set up indirect costs for a project.

## An indirect cost without compounding rules

You want to add per diem expenses as an indirect cost on a project. You can set up the indirect cost as 10 percent of the hourly rate. Alternatively, you can set up the indirect cost as 10.00 per hour. If the worker’s hourly rate is 50.00, for every hour that the worker works on the project, the project is charged one of the following indirect cost amounts:

  - Using a percentage of the hourly rate, indirect costs are 5.00 per hour: (10 percent \* 50)

  - Using a specific amount per hour, indirect costs are 10.00 per hour.

## Multiple indirect costs without compounding rules

You want to record per diem and travel costs as indirect costs for a project. You set up the indirect costs as a percentage of the hourly rate. The indirect costs are added to a project by using the following method:

  - Hourly rate for the worker = 50.00 per hour

  - Indirect cost A for travel: 10 percent of the hourly rate

  - Indirect cost B for per diem: 6 percent of the hourly rate

  - For every hour worked, a total amount of 8.00 is added to the project as an indirect cost: indirect cost A (50 \* 10 percent = 5) + indirect cost B (50 \* 6 percent = 3).

## Multiple indirect costs with compounding rules

You want to set up two indirect costs for a project, and you want to calculate a third indirect cost by using the first two indirect costs as the base amount for the calculation. You can create compounding rules for indirect costs related to the cost, revenue, and invoice amounts for the project. If you use compounding rules, you must set up the indirect costs so that they are charged as a percentage of the hourly rate.

  - Hourly rate for the worker = 50.00 per hour

  - Indirect cost A for travel: 10 percent of the hourly rate

  - Indirect cost B for per diem: 6 percent of the hourly rate

  - Indirect cost C by using a compounding rule: ((indirect cost A + indirect cost B) \* 10 percent).

  - For every hour worked, a total amount of 8.80 is added to the project as an indirect cost: indirect cost A (50 \* 10 percent = 5) + indirect cost B (50 \* 6 percent = 3) + compounding rule C (((A+B) \* 10 percent) = .80).

## See also

[Key tasks: Create and maintain indirect costs](key-tasks-create-and-maintain-indirect-costs.md)

[Indirect cost component (form)](https://technet.microsoft.com/library/hh208810\(v=ax.60\))

[Indirect cost component groups (form)](https://technet.microsoft.com/library/hh209621\(v=ax.60\))

[Assigned indirect cost components (form)](https://technet.microsoft.com/library/hh209589\(v=ax.60\))

[Indirect cost component group assignment rules (form)](https://technet.microsoft.com/library/hh227451\(v=ax.60\))

[Indirect component transaction (form)](https://technet.microsoft.com/library/hh209467\(v=ax.60\))

  


