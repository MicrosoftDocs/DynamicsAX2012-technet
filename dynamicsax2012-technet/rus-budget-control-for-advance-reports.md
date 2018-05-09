---
title: (RUS) Budget control for advance reports
TOCTitle: (RUS) Budget control for advance reports
ms:assetid: 25a23f72-d4e3-47a4-a6d6-8d71df5ae172
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733189(v=AX.60)
ms:contentKeyID: 49685157
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Budget control for advance reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

By using budget control, you can make sure that sufficient funds are available for planned or actual purchases. After you set up basic budgeting, you can set up budget control. You can use budget control to confirm whether budget funds are available on source documents, such as purchase orders, expense reports, advance reports, and accounting journals. If the budget funds exceed the budget limit that is set, additional processing of the document can be prevented.

An advance report is primarily used to report travel expenses that are incurred by an employee during a business trip. If the expenses that are incurred on an advance report exceed the budget that is set, budget control indicates that the funds are not available.

To enable budget control for advance reports, follow these steps.

  - In the **Budget control configuration** form, in the **Select source documents** area, select advance reports as a source document for budget control, and enable budget checks for advance report lines.

  - In the **Budget control configuration** form, in the **Budget funds available** area, define the calculation that determines whether budget funds for advance reports are available.

## Budget calculation

When you define the budget calculation for advance reports, you should take actual expenditures and unposted actual expenditures into account.

**Example**

Budget funds available = (**Original budget** + **Budget revisions** + **Budget transfers**) – (**Actual expenditures** + **Unposted actual expenditures**)

You can view the actual expenditures and unposted actual expenditures for each advance report line in the **Actual expenditures** form.

## Budget checking

Budget checking for advance reports makes sure that budget funds are available for planned or future expenditures. The budget checking process runs automatically when an advance report line is saved, or when the report is posted.

## See also

[(RUS) Budget control configuration (modified form)](https://technet.microsoft.com/en-us/library/jj733403\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

