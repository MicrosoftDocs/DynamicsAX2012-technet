---
title: Create a workflow
TOCTitle: Create a workflow
ms:assetid: 5e1cceef-ef9d-4b14-a7fa-9351529e6868
ms:mtpsurl: https://technet.microsoft.com/library/Gg731809(v=AX.60)
ms:contentKeyID: 35132655
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- workflow
audience: Application User
ms.search.region: Global
---

# Create a workflow 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the following procedures to create a workflow.

## Open the workflow editor

The Microsoft Dynamics AX module that you are working in determines the types of workflow that you can create. Follow these steps to select the type of workflow to create and to open the workflow editor.

1.  Go to the module for which you want to create a new workflow.
    
    For example, if you want to create a workflow for purchase requisitions, go to the **Procurement and sourcing** module. For a list of the workflows that you can create in each module, see [Workflow types](workflow-types.md).

2.  Click **Setup** \> **\[Module name\] workflows**. A list page is displayed.

3.  On the Action Pane, click **New**. The **Create workflow** form is displayed.

4.  Select the type of workflow to create. Click **Create workflow**.
    
    The workflow editor is displayed. Use the following procedures to design the workflow.

## Drag workflow elements onto the canvas

The **Workflow elements** area of the workflow editor contains the elements that you can add to your workflow. Drag the elements that you want to use onto the canvas.

## Connect the elements

To connect one workflow element to another, hold the pointer over an element until connection points appear. Click a connection point and drag it to another element. Be sure to connect all the elements.

## Configure the properties of the workflow

Use the following steps to configure the properties of the workflow.

1.  Click the canvas to make sure that no workflow element is selected.

2.  Click **Properties** to open the **Properties** form for the workflow.

3.  Follow the procedures that are listed in [Configure the properties of a workflow](configure-the-properties-of-a-workflow.md).

## Configure the elements of the workflow

Configure each element that you dragged onto the canvas. For information about how to configure each workflow element, see [Configure workflow elements](configure-workflow-elements.md).

## Resolve any errors or warnings

The **Errors and warnings** pane, located at the bottom of the workflow editor, displays messages that have been generated for the workflow. To locate the element where an error or warning occurs, double-click the error or warning message.

All errors and warnings must be resolved before you can make the workflow active.

## Save and activate the workflow

When you are ready to save and activate the workflow, follow these steps.

1.  Click **Save and close** to close the workflow editor and to open the **Save workflow** form.

2.  Enter comments about the changes that you have made to the workflow.

3.  Click **OK**.

4.  If all errors and warnings have been resolved, the **Activate workflow** form is displayed. Select one of the following options:
    
      - To activate this version of the workflow, click **Activate the new version**. When a workflow is active, users can submit documents to it for processing.
    
      - If you do not want to activate this version, click **Do not activate the new version**. You can activate the workflow later. For more information, see [Activate a workflow](activate-a-workflow.md).

  


