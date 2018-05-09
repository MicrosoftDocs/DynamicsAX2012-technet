---
title: About utilization rates
TOCTitle: About utilization rates
ms:assetid: 03398403-c17d-4c73-9be9-d768cec71c4e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg230654(v=AX.60)
ms:contentKeyID: 42117747
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- billable rate
- efficiency rate
- utilization rate
---

# About utilization rates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The utilization rate is the percentage of time that a worker engages in billable work or productive work in a specific working period. Billable hours are the worker’s hours that can be charged to a customer.

To calculate a worker’s utilization rate, the system divides the number of billable hours by the number of working hours in a specific time period.

For example, if the worker has 30 billable hours in a time period and the number of working hours in that same time period is 40, the worker’s utilization rate is 75%.

When you calculate the utilization rate of a worker, you can calculate either the billable rate or the efficiency rate:

  - **Billable rate** – The billable rate is the difference between billable hours and non-billable hours or norm hours.

  - **Efficiency rate** – The efficiency rate is the difference between productive hours vs. non-productive hours or norm hours. Productive hours are the hours that are spent contributing to a specific project. Productive hours are typically billed to customers, except in the case of internal projects. Non-productive hours are never billed to a customer.

You calculate utilization rates in the **Hour utilization** form. The calculations are based on default preferences that you set up in the **Project management and accounting parameters** form. In the **Project management and accounting parameters** form, you can specify how hours are calculated by assigning one of the following options to each project type. This applies for both billable rate calculations and efficiency rate calculations.

  - **Utilization** – Hours that are reported for the selected project type are always considered billable or efficiency utilization.

  - **Burden** – Hours that are reported for the selected project type are always considered non-billable or non-efficiency utilization.

  - **According to line property** – The line properties of a particular hour transaction determine whether the hours are considered for billable or efficiency utilization.

  - **Not included** – Hours are not factored into the calculation of billable or efficiency utilization.

In the **Hour utilization** form, along with the overall utilization rate percentage for a worker or a project, you can view the number of hours that went into the utilization rate calculation for each of the following hour types:

  - **Not included hours** – Not included hours are not included in the hour utilization rate.

  - **Included hours** – Included hours are calculated by adding the utilization hours and burden hours. These hours are included in the utilization rate.

  - **Burden hours** – Burden hours are equivalent to non-chargeable hours when you are calculating a billable rate. They are equivalent to non-productive hours when you are calculating an efficiency rate.

  - **Utilization hours** – Utilization hours are equivalent to chargeable hours when you are calculating a billable rate. They are equivalent to productive hours when you are calculating an efficiency rate.

When you calculate the utilization rate for a worker, you can use norm hours or included hours. If you use included hours, you must ensure that workers record all their working time for the timesheet periods. This is because the calculation is expressed as a percentage of hours entered. When you calculate the hour utilization rate for a project, project contract, customer record, or category, you must use included hours for your calculation.

## See also

[Utilization hours (form)](https://technet.microsoft.com/en-us/library/hh208657\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

