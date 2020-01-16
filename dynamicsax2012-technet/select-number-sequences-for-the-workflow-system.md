---
title: Select number sequences for the workflow system
TOCTitle: Select number sequences for the workflow system
ms:assetid: c7b874ee-13a9-43c6-958b-d5715a1ce4db
ms:mtpsurl: https://technet.microsoft.com/library/Gg731929(v=AX.60)
ms:contentKeyID: 35132862
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Select number sequences for the workflow system 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An identification number is automatically assigned to every workflow that is created and every instance of a workflow that is generated. The identification numbers are based on number sequences. This topic provides information that will help you create number sequences. It also describes how to specify which number sequence is used to generate IDs for workflows, and which number sequence is used to generate IDs for workflow instances.

## Create number sequences

Create number sequences so that identification numbers can be assigned to workflows and workflow instances. To create number sequences, see [Set up number sequences](set-up-number-sequences.md).

## Specify the number sequences that are used to generate workflow IDs and workflow instance IDs

To specify which number sequences are used to generate workflow IDs and workflow instance IDs, complete the following procedure.

1.  Click **System administration** \> **Setup** \> **System parameters**.

2.  Click **Number sequences**.

3.  On the **Workflow ID** row, in the **Number sequence code** field, select the number sequence to use to generate workflow IDs.

4.  On the **Instance ID** row, in the **Number sequence code** field, select the number sequence to use to generate workflow instance IDs.

  


