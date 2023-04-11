---
title: About evidence
TOCTitle: About evidence
ms:assetid: 3029e174-33c8-416d-8d58-93e1d44ecf24
ms:mtpsurl: https://technet.microsoft.com/library/Hh271490(v=AX.60)
ms:contentKeyID: 36384122
author: tonyafehr
ms.author: daxcpft
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About evidence 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the context of compliance, evidence provides proof that a control exists and is working correctly.

You can add a link to a piece of evidence or describe it for each instance of a document that is listed on the **Internal controls** page. Evidence can be located in the **Process documentation** folder or on a website. You can also edit evidence that is in electronic format. For more information, see [Examples: Internal controls](examples-internal-controls.md).

## Upload evidence to the Process documentation folder

1.  Click **Compliance** on the top link bar, and then click **Process documentation** on the Quick Launch. The contents of the **Process documentation** folder are displayed.

2.  Click **Add document**.

3.  Select the file or files to upload and then click **OK**.

## Add evidence to an internal control document

1.  Click **Compliance** on the top link bar, and then click **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, select a document.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  In the **Evidence** section, select one of the following options:
    
      - To link to evidence located on a website, click **Add evidence via URL** and enter the URL.
        

        > [!NOTE]
        > <P>The URL must contain http://, https://, or ftp:// to be an active link.</P>

    
      - To link to evidence in the **Process documentation** folder, click **Add evidence from process documentation**, select the file, and then click **Add**.

5.  Click the **Update line** icon.

6.  Click **Save**.

## Edit uploaded evidence

1.  Click **Compliance** on the top link bar, and then click **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, select the document that contains the link to the evidence that you want to modify.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  In the **Evidence** section, click the **Edit line** icon for the file that you want to modify.

5.  In the **Edit document** column, click the **Edit document** icon.

6.  Make changes and save the document.

7.  On the **Edit document** page, click the **Update line** icon.

8.  Click **Save**.

## Remove an evidence link

1.  Click **Compliance** on the top link bar, and then click **Internal controls** on the Quick Launch.

2.  On the **Internal controls** page, select the document that contains the evidence link that you want to remove.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  In the **Evidence** section, in the **Remove** column of the evidence row, click the **Remove** icon.

## Troubleshoot evidence

## I made changes to an evidence attachment, and saved and closed the document. When I reopen the document, I cannot see the changes.

When you attach files that were created by using business applications other than the Microsoft Office System, the changes are saved to the local hard disk and not to the **Compliance** site.

Edit the evidence document on the hard disk and then upload it to the **Compliance** site.

## I removed evidence, but I am still getting a prompt to overwrite it when I attempt to add new evidence.

Deleting an evidence attachment removes the link to the attachment, but does not remove the attachment from the **Compliance** site. Do one of the following:

  - Overwrite the original attachment.

  - Rename the attachment.

## See also

[Examples: Internal controls](examples-internal-controls.md)

[About process documentation](about-process-documentation.md)

  


