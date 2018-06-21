---
title: Set up workflow for retail catalogs
TOCTitle: Set up workflow for retail catalogs
ms:assetid: 90c827d4-3286-482e-bd54-52c4a45d0f68
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ728696(v=AX.60)
ms:contentKeyID: 49556625
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- set up catalogs
---

# Set up workflow for retail catalogs [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up workflow for retail catalogs, so that the catalog products can be reviewed and approved before they are published. When you set up the workflow process for retail product catalogs, you have two options. The workflow process can approve the retail product catalogs automatically, without manual intervention, or you can route the catalogs to one or more reviewers for review and approval. A retail product catalog must be approved before it can be published.

For an overview of workflow in Microsoft Dynamics AX, see [Overview of the workflow system](overview-of-the-workflow-system.md) and [Workflow concepts](workflow-concepts.md). For information about how to set up workflows, see [Configuring the workflow system](configuring-the-workflow-system.md).

1.  Click **Retail** \> **Setup** \> **Retail workflows**.

2.  On the **Retail workflows** list page, on the **Action Pane**, click **New**.

3.  In the **Create workflow** dialog box, select **Retail catalog approval workflow** as the workflow type, and then click **Create workflow**.

4.  In the **Retail catalog approval workflow** form, in the **Workflow elements** pane, select the **Retail catalog workflow approve** workflow element, and then drag this element onto the **Workflow** canvas.

5.  Connect the elements on the workflow canvas. To connect one workflow element to another, hold the pointer over an element until connection points appear. Click a connection point, and then drag it to another element. Be sure to connect all the elements.

6.  Configure each element of the workflow to enable automatic or manual approval. For more information about how to configure a workflow, see [Configuring the workflow system](configuring-the-workflow-system.md).

7.  After the workflow elements are configured, follow these steps:
    
    1.  Click **Save and close**.
    
    2.  In the **Retail catalog approval workflow** dialog box, enter any notes for the version of the workflow, and then click **OK**.
    
    3.  To activate the workflow, in the **Retail catalog approval workflow** dialog box, select the **Activate the new version** option, and then click **OK**.

## See also

[Key tasks: Create retail product catalogs](key-tasks-create-retail-product-catalogs.md)

[Workflows (list page)](https://technet.microsoft.com/en-us/library/hh209721\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

