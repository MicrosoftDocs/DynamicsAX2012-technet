---
title: About the workflow editor
TOCTitle: About the workflow editor
ms:assetid: 8c3a062a-eb98-4bf4-a755-5c5e46a81bb2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731853(v=AX.60)
ms:contentKeyID: 35132717
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- workflow
- workflow editor
audience: Application User
ms.search.region: Global
---

# About the workflow editor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The workflow editor is a graphical user interface (GUI) that you can use to create Microsoft Dynamics AX workflows by arranging workflow elements on a design surface. The process resembles the process for modeling a business process by using Microsoft Visio. You can add, delete, and reposition elements that represent the tasks and approvals that make up the workflow. You can also add flow-controls, such as manual decisions, automated decisions, and parallel activities. As a result, you can create complex workflows that exactly model the business processes that you want to automate. The following figure illustrates the areas of the workflow editor.

![Workflow editor](images/Gg731853.Workflow_WorkflowEditor(AX.60).gif "Workflow editor")

The workflow editor consists of the following areas:

  - **Action pane** – The action pane is located at the top of the workflow editor. The action pane contains buttons that you can use to navigate in the workflow, copy and paste workflow elements, and configure properties. To configure properties of the whole workflow, select the canvas. To configure properties of a specific workflow element, select the element.

  - **Workflow elements** – This area contains the workflow elements that you can add to the workflow that you are creating. To add elements, drag them from the **Workflow elements** area onto the canvas.

  - **Canvas** – The canvas is the main area where you arrange the workflow elements. The flow of the business process that you are modeling is indicated by connectors that join the elements.
    
    Some elements contain other elements. When elements contain other elements, a parent-child relationship is created. For example, an approval element contains one or more approval steps. The approval steps are child elements of the parent approval element. To configure the child elements, double-click the parent element.

  - **Navigation bar** – The navigation bar is used to navigate between parent elements and child elements.

  - **Errors and warnings pane** – This pane is located at the bottom of the workflow editor. The pane displays error and warning messages that have been generated for the workflow. These errors and warnings must be resolved before you can activate the workflow. To locate the element where an error or warning occurs, double-click the error or warning message.

## See also

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  


