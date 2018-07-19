---
title: Workflow with roles
TOCTitle: Workflow with roles
ms:assetid: fcd1a96d-b08d-4a07-a0b4-8b7ce0b0fff7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg723987(v=AX.60)
ms:contentKeyID: 35133339
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Workflow with roles 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following figure shows an example of a workflow for an expense report. This workflow includes elements that are assigned to roles rather than specific users.

![Workflow with elements that are assigned to roles](images/Gg723987.Workflow_Role(AX.60).gif "Workflow with elements that are assigned to roles")

To understand how a document moves through this workflow, assume that Sam has submitted an expense report totaling USD 7,000 and has routed his receipts to Accounts payable. In this scenario, a user assigned to the Accounts payable clerk role must review the receipts that Sam routed. After the Accounts payable clerk has finished reviewing the receipts, Sam's manager and the controller must approve the expense report.

Because the total amount is not more than USD 10,000, the CEO does not have to approve the expense report. Therefore, after the controller approves the expense report, the workflow ends.

  


