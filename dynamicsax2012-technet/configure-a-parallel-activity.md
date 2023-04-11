---
title: Configure a parallel activity
TOCTitle: Configure a parallel activity
ms:assetid: 6c2aca74-ac9a-410e-a138-28000e2245f6
ms:mtpsurl: https://technet.microsoft.com/library/Gg731827(v=AX.60)
ms:contentKeyID: 35132676
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure a parallel activity 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure a parallel activity, complete the following procedures in the workflow editor.

## Name the parallel activity

Follow these steps to enter a name for the parallel activity.

1.  Right-click the parallel activity and then click **Properties** to open the **Properties** form.

2.  In the left pane, click **Basic Settings**.

3.  In the **Name** field, enter a unique name for the parallel activity.

4.  Click **Close**.

## Configure the branches of the parallel activity

A parallel activity consists of workflow branches that run at the same time. Follow these steps to add and configure the branches of this parallel activity.

1.  Double-click the parallel activity to display the branches of the parallel activity.

2.  To add a branch, drag the **Branch** element from the **Workflow elements** area to an insertion point on the canvas. The following figure shows an insertion point.
    
    ![Insertion point](images/Gg731827.Workflow_InsertionPoint(AX.60).gif "Insertion point")
    

    > [!NOTE]
    > <P>The order of the branches is not important because all the branches of a parallel activity run at the same time.</P>



3.  To configure each branch, see [Configure a parallel branch](configure-a-parallel-branch.md).

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  


