---
title: Workflow with a conditional decision
TOCTitle: Workflow with a conditional decision
ms:assetid: c344c2aa-ea34-4081-9713-455ef069d49b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ618308(v=AX.60)
ms:contentKeyID: 49105577
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Workflow with a conditional decision 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A conditional decision is a point at which a workflow divides into two branches. At that point, Microsoft Dynamics AX automatically decides which branch to use by evaluating the submitted document to determine whether it meets specified conditions.

To better understand how a document moves through a workflow that includes a conditional decision, review the following diagram. The diagram shows an example of a workflow that is used to post vendor invoices.

![Workflow with a conditional decision](images/JJ618308.Workflow_WithConditionalDecision(AX.60).gif "Workflow with a conditional decision")

Assume that April has submitted a vendor invoice that totals USD 12,000. In this scenario, the following events occur:

1.  Microsoft Dynamics AX reviews the policy rules for vendor invoices and identifies a policy rule that requires vendor invoices that total USD 10,000 or more to be approved before they are paid.

2.  Michael reviews vendor invoice matching information and looks for discrepancies.

3.  Microsoft Dynamics AX evaluates the submitted invoice against the policy rule. Because this vendor invoice is for USD 12,000, Microsoft Dynamics AX assigns it to Phyllis for approval.

4.  Phyllis approves the invoice.

5.  Microsoft Dynamics AX automatically posts the invoice.

Now assume that April submits another vendor invoice that totals USD 9,000. In this scenario, the following events occur:

1.  Microsoft Dynamics AX reviews the policy rules for vendor invoices and identifies a policy rule that requires vendor invoices that total USD 10,000 or more to be approved before they are paid.

2.  Michael reviews vendor invoice matching information and looks for discrepancies.

3.  Microsoft Dynamics AX evaluates the submitted invoice against the policy rule. Because this vendor invoice is for USD 9,000, Phyllis does not need to approve it.

4.  Microsoft Dynamics AX automatically posts the invoice.

## See also

[Configure a conditional decision](configure-a-conditional-decision.md)

  


