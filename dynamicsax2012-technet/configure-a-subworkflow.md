---
title: Configure a subworkflow
TOCTitle: Configure a subworkflow
ms:assetid: d04b9e99-1c47-4cb4-8664-1ebc60c7a624
ms:mtpsurl: https://technet.microsoft.com/library/Dd362080(v=AX.60)
ms:contentKeyID: 35132896
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure a subworkflow 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure a subworkflow, in the workflow editor, right-click the subworkflow and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties of the subworkflow.

## Name the subworkflow

Follow these steps to enter a name for the subworkflow.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the subworkflow.

## Select the workflow that runs when the subworkflow element is executed

A subworkflow runs in the context of a parent workflow. Follow these steps to select the workflow that runs when this subworkflow element is executed.

1.  In the left pane, click **Basic Settings**.

2.  From the **Subworkflow** list, select an existing workflow.

## Select the type of document that is processed by the subworkflow

To select the type of document that is processed by the subworkflow, you must select the field that represents the association to the document.

1.  In the left pane, click **Basic Settings**.

2.  From the **Field** list, select the field that represents the association to the document.

## Indicate whether the subworkflow must finish processing before the next element is executed

Follow these steps to indicate whether the subworkflow must finish processing before the next element in the parent workflow is executed.

1.  In the left pane, click **Basic Settings**.

2.  Indicate whether the subworkflow must finish processing before the next element in the parent workflow is executed.
    
      - If the subworkflow must finish processing, click **Wait for the subworkflow to complete before continuing**.
    
      - If the subworkflow is not required to finish processing before the next element in the parent workflow is executed, click **Do not wait for the subworkflow to complete**.

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  


