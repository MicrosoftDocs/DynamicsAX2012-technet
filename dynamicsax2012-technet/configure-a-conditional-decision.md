---
title: Configure a conditional decision
TOCTitle: Configure a conditional decision
ms:assetid: 5b943175-4362-4f45-82f5-6ea86fbeda5b
ms:mtpsurl: https://technet.microsoft.com/library/Gg731801(v=AX.60)
ms:contentKeyID: 35132646
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure a conditional decision 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure a conditional decision, in the workflow editor, right-click the conditional decision, and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties of the conditional decision.

## Name the decision

Follow these steps to enter a name for the conditional decision.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the conditional decision.

## Set conditions

A conditional decision is a point at which a workflow divides into two branches. The system determines which branch is used by evaluating the submitted document to determine whether it meets specific conditions.

1.  In the left pane, click **Basic Settings**.

2.  Click **Add condition**.

3.  Enter a condition.

4.  Enter additional conditions, if they are required.

5.  To verify that the conditions that you entered are configured correctly, complete the following steps:
    
    1.  Click **Test** to open the **Test workflow condition** form.
    
    2.  Select a record in the **Validate condition** area of the form.
    
    3.  Click **Test**. The system evaluates the record to determine whether it meets the conditions that you defined.
    
    4.  Click **OK** or **Cancel** to return to the **Properties** form.

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  


