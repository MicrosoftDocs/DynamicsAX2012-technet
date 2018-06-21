---
title: Configure a line-item workflow
TOCTitle: Configure a line-item workflow
ms:assetid: d1e15e0a-4bc8-4868-9417-29f1c0115974
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731961(v=AX.60)
ms:contentKeyID: 35132901
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure a line-item workflow [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure a line-item workflow element, in the workflow editor, right-click the element and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties of the line-item workflow element.

## Name the line-item workflow element

Follow these steps to enter a name for the line-item workflow element.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the line-item workflow element.

## Specify whether the same workflow is used to process all line items

Follow these steps to specify whether the same workflow is used to process all line items on a document.

1.  In the left pane, click **Basic Settings**.

2.  If the same workflow should process all the line items on a document, click **Invoke a single workflow for all line-items**. Then select the workflow to use to process the line items.

3.  If a specific workflow should process line items that meet a certain set of conditions, click **Invoke a workflow for each line-item**.
    
    To define the set of conditions, follow these steps:
    
    1.  Click **Add**.
    
    2.  Select the condition in the table.
    
    3.  On the **Condition name** tab, enter a name for the set of conditions that you are defining.
    
    4.  Click **Add condition** to enter a condition.
    
    5.  Enter additional conditions, if they are required.
    
    6.  To verify that the set of conditions that you entered is configured correctly, click **Test**. The **Test workflow condition** form is displayed.
        
        Select a record in the **Validate condition** area of the form, and then click **Test**. The system evaluates the record to determine whether it meets the set of conditions that you defined.
        
        Click **OK** or **Cancel** to return to the **Properties** form.
    
    To specify the workflow that is used to process line items that meet the set of conditions, follow these steps:
    
    1.  Click the **Workflow** tab.
    
    2.  Select the workflow from the list.

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

