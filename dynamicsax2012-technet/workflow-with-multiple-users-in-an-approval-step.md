---
title: Workflow with multiple users in an approval step
TOCTitle: Workflow with multiple users in an approval step
ms:assetid: a1254679-38db-4325-90d9-838790d0978c
ms:mtpsurl: https://technet.microsoft.com/library/Gg731883(v=AX.60)
ms:contentKeyID: 35132791
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Workflow with multiple users in an approval step 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following figure shows an example of a workflow for an expense report. The workflow includes an approval process that has three approval steps. In the second approval step, the document requires approval from three people: Sue, Jo, and Bill.

![Workflow that has an approval process](images/Gg731883.Workflow_MultipleUsersInStep(AX.60).gif "Workflow that has an approval process")

When an approval step has multiple approvers, the action that is applied to the document is determined either by the first person who responds or by the people who respond.

You must select one of the following options when you configure an approval step that has multiple approvers.

## Single approver

If you select this option, the action that is applied to the document is determined by the first person who responds.

For example, assume that Sam has submitted an expense report for USD 15,000. The document is currently assigned to Sue, Jo, and Bill. If Sue is the first person who responds to the document, the action that she takes is applied to the document.

  - If Sue approves the document, it is sent to Ann for approval.

  - If Sue rejects the document, it is rejected and sent back to Sam.

## Majority of approvers

If you select this option, the action that is applied to the document is determined when most of the approvers respond.

For example, assume that Sam has submitted an expense report for USD 15,000. The document is currently assigned to Sue, Jo, and Bill. If Sue and Jo are the first two approvers who respond, the action that they take is applied to the document.

  - If both Sue and Jo approve the document, it is sent to Ann for approval.

  - If Sue approves the document, but Jo rejects it, the document is rejected and sent back to Sam.

## Percentage of approvers

If you select this option, the action that is applied to the document is determined when a specific percentage of the approvers respond.

For example, assume that Sam has submitted an expense report for USD 15,000. The document is currently assigned to Sue, Jo, and Bill, and you entered **50** as the percentage. If Sue and Jo are the first two approvers who respond, the action that they take is applied to the document, because they meet the requirement for 50 percent of the approvers.

  - If both Sue and Jo approve the document, it is sent to Ann for approval.

  - If Sue approves the document, but Jo rejects it, the document is rejected and sent back to Sam.

## All approvers

If you select this option, all the approvers must approve the document. Otherwise, the workflow cannot continue.

For example, assume that Sam has submitted an expense report for USD 15,000. The document is currently assigned to Sue, Jo, and Bill.

  - If Sue, Jo, and Bill all approve the document, it is sent to Ann for approval.

  - If one person rejects the document, it is rejected and sent back to Sam.

  


