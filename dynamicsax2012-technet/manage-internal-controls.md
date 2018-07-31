---
title: Manage internal controls
TOCTitle: Manage internal controls
ms:assetid: fa736577-3037-4eee-ac31-c4bd803a7c8c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh299231(v=AX.60)
ms:contentKeyID: 36384337
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- controls
- EditDocument
audience: Application User
ms.search.region: Global
---

# Manage internal controls 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Internal controls** page, which displays the structure of the **Internal controls** site, to manage documents on the **Compliance** site. Each node of this structure can contain a document folder where all documents for that location are stored. The permissions granted by the **Compliance** site administrator determine which document folders you can view. You can add, edit, and remove documents by using the **Internal controls** site. A document template defines the properties and workflow steps for documents, the order in which each document can be nested or grouped, and how they are grouped. For more information, see [About compliance document templates](about-compliance-document-templates.md).

When you create documents, there is a relationship between the various document types, which are determined by the template that is selected. Most document types have a child document or parent document that dictates how the documents are related. This relationship is established when you create the documents. For an example of how the document types are used, see [Examples: Internal controls](examples-internal-controls.md).

You can view a list of evidence that is associated with a selected document, and property information about that document, on the **Internal controls** page.

You can use the default controls library to plan which control documents and properties you will enter on the **Internal controls** page. The default controls library is located in the **Compliance resources** shared documents folder.

## Create a document

1.  Click **Compliance** on the top link bar, and then click **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, select the document folder where you want to add a document.

3.  On the **Action Pane**, in the **New** group, click **Add document**.

4.  In the **Create document** dialog box, enter a name and select the document template to use.

5.  Click the **Create and edit** button.

6.  On the **Edit document** page, enter an owner. This is typically the person who is responsible for the process, control, or test.
    

    > [!NOTE]
    > <P>This user must be set up as a user on the Enterprise Portal for Microsoft Dynamics AX SharePoint site.</P>



7.  Set properties and workflow assignments, as required by the document template.

8.  Click **Save**.

## View or modify a document

1.  Click **Compliance** on the top link bar, and then click **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, select the document to modify.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  To modify the document, make changes on the **Edit document** page, and then click **Save**.
    

    > [!NOTE]
    > <P>If you do not have sufficient privileges, the <STRONG>Save</STRONG> button is not available.</P>



## Remove a document

1.  Click **Compliance** on the top link bar, and then click **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, select the document to remove.

3.  On the **Action Pane**, in the **Maintain** group, click **Delete**.

## Set up compliance workflow steps for a document

If a document template contains a workflow section, you must modify the first line that is created by default. If you do not, the **Completed** check box will not appear for the subsequent assignments for that step.

1.  Click **Compliance** on the top link bar, and then click **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, select the document to modify.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  On the **Edit document** page, in the **Workflow** section, under a workflow step, click the **Edit line** icon.

5.  In the **Assigned to** column, enter the user who is responsible for the step, in the following format: domain\\alias
    

    > [!NOTE]
    > <P>This user must be set up as a user on the Enterprise Portal SharePoint site.</P>



6.  Click the **Validate user** icon.

7.  Click the **Update line** icon.

8.  Click **Save**.

## Roll back a compliance workflow step

When you roll back a workflow step, all subsequent steps are also rolled back. The **Complete** check box is cleared and the step or steps must be repeated.

1.  Click **Compliance** on the top link bar, and then click **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, select the document to modify.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  On the **Edit document** page, in the **Workflow** section, select the compliance workflow step to roll back and then click the icon in the **Rollback** column.

## Troubleshoot managing internal controls

## I cannot add a document to the Internal controls site.

You must have **Add/Copy** permissions or higher to add documents to the **Internal controls** site; these permissions are granted by using the **Set up control environment** page.

  - Contact the **Compliance** site administrator to request the appropriate permissions.

## I cannot complete a task that is assigned to me.

You must have **Edit** permissions or higher to complete assigned tasks; these permissions are granted by using the **Set up control environment** page.

  - Contact the **Compliance** site administrator to request the appropriate permissions.

## I created a document and cannot make any changes.

Your permissions may have been changed after you created the document. You must have **Edit** permissions or higher to modify a document; these permissions are granted by using the **Set up control environment** page.

  - Contact the **Compliance** site administrator to request the appropriate permissions.

## My new document has a status of Complete.

  - By default, documents that do not contain a workflow section are set to Complete.

## See also

[About compliance](about-compliance.md)

[Set up the Internal controls site](set-up-the-internal-controls-site.md)

[Edit document templates](edit-document-templates.md)

[About evidence](about-evidence.md)

[About process documentation](about-process-documentation.md)

  


