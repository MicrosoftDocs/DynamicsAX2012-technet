---
title: Indicate that a workflow is the default workflow
TOCTitle: Indicate that a workflow is the default workflow
ms:assetid: 6b4c6e81-eebc-4f31-a811-0848612d9438
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh202067(v=AX.60)
ms:contentKeyID: 35949309
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Indicate that a workflow is the default workflow 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create multiple workflows of the same type. For example, you can have the following purchase requisition workflows:

  - **Purchase Requisitions Denmark** – This workflow is used when country/region = DK.

  - **Purchase Requisitions Spain** – This workflow is used when country/region = ES.

When you have multiple workflows of the same type, you must specify which workflow is the default workflow. Documents that do not meet any of the activation conditions are processed by the default workflow.

For example, if a new employee in Norway submits a purchase requisition for approval, that purchase requisition does not meet any of the sample workflow activation conditions. In this scenario, the purchase requisition is processed by the workflow that is specified as the default workflow.

Follow these steps to specify that a workflow is the default workflow for a specific workflow type.

1.  Open the module that contains the workflow that you want to select as the default workflow for a specific workflow type.

2.  Click **Setup** \> **\[Module name\] workflows**. A list page is displayed.

3.  Select the workflow to use as the default workflow for a specific workflow type.

4.  On the Action Pane, click **Set as default**.

  


