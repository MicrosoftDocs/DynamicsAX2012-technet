---
title: About expense reports and multiple approvers
TOCTitle: About expense reports and multiple approvers
ms:assetid: 12f35be2-a3d2-430f-b9df-ff83c1a9a300
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580573(v=AX.60)
ms:contentKeyID: 39519052
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About expense reports and multiple approvers [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Depending on the expense approval policies of your organization, more than one person may be required to approve an expense report that is submitted by an employee. When you are setting up the workflow process for expense report approval, you can add workflow elements that include tasks or steps for one or more expense report approvers. For example, you might require that all expense reports be approved first by the manager of the employee who submitted the report, and then by the accounts payable coordinator.

If you decide to require multiple expense report approvers, you can add the workflow elements in any of the following ways:

  - One approval element that contains one step. For example, the step might require that an expense report be assigned to a user group and that it be approved by 50% of the user group members.

  - One approval element that contains multiple steps. For example, the steps in the approval element are as follows:
    
    1.  The manager of the employee who submitted the expense report approves it.
    
    2.  The accounts payable clerk verifies the receipts and expense report items.
    
    3.  The budget owner approves the expense report.

  - Multiple approval elements, where each element contains one step. For example, the approval elements are as follows:
    
    1.  The employee’s manager approves the expense report.
    
    2.  The budget owner approves the expense report.

## See also

[About Travel and expense workflow](about-travel-and-expense-workflow.md)

[Configure workflows](configure-workflows.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

