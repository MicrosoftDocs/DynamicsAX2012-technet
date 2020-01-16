---
title: Configure and use Microsoft Dynamics AX document management with Microsoft SharePoint document libraries
TOCTitle: Configure and use document management with Microsoft SharePoint document libraries
ms:assetid: 07fc5e47-a916-4839-ad47-f98196d6d3a1
ms:mtpsurl: https://technet.microsoft.com/library/Dn631953(v=AX.60)
ms:contentKeyID: 61542607
author: Khairunj
ms.date: 09/17/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure and use Microsoft Dynamics AX document management with Microsoft SharePoint document libraries 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic includes information about how you can configure document management to integrate with Windows SharePoint document libraries in Microsoft Dynamics AX 2012 R2 or later versions of Microsoft Dynamics AX. After you configure document management and set up document libraries in SharePoint, you can save document attachments to SharePoint and you can store document templates in a SharePoint document library.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 or later</p></td>
</tr>
<tr class="even">
<td><p>Related configuration tasks</p></td>
<td><p>Activate document management. For more information, see <a href="configure-document-management.md">Configure document management</a>.</p>
<p><a href="set-up-integration-with-microsoft-office-add-ins.md">Set up integration with Microsoft Office Add-ins</a></p></td>
</tr>
<tr class="odd">
<td><p>Other products</p></td>
<td><p>Windows SharePoint</p>
<p>You must create or have access to one or more document libraries before completing the procedures in this topic. For more information, see <a href="https://technet.microsoft.com/library/cc262215.aspx">Plan document libraries in SharePoint</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Specify authentication types for SharePoint sites

In order to interact with documents in SharePoint from Microsoft Dynamics AX, you must specify the authentication type for each SharePoint site that you want Microsoft Dynamics AX to integrate with. In this instance, authentication refers to the process that Microsoft Dynamics AX uses to determine whether the user has permission to access the SharePoint site.

To specify the authentication type for a SharePoint site, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document management parameters**.

2.  Click Add.

3.  Enter the URL for the SharePoint site.

4.  Select the authentication type for the SharePoint site. Use the information in the following table to decide which authentication type is best for you.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Type</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Windows</strong></p></td>
    <td><p>Select this option if the SharePoint server is on the local network.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>SharePoint Online</strong></p></td>
    <td><p>Select this option if the SharePoint server is in the Cloud.</p></td>
    </tr>
    </tbody>
    </table>


## 2\. Create document types for SharePoint document libraries

Before you can save an attachment or template to SharePoint, you must create a document type for the following kinds of documents:

  - Document attachments – These are documents that are saved on your computer, and that you want to attach to a Microsoft Dynamics AX record and save to a SharePoint document library.

  - Document templates – These are templates that you have set up, and that you want to reuse frequently when you complete various business processes, such as processing sales orders.

To create document types for SharePoint, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Click **New** and then enter the following information.
    
    **For document attachments**
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Class</p></td>
    <td><p>Attach file</p></td>
    </tr>
    <tr class="even">
    <td><p>Group</p></td>
    <td><p>File</p></td>
    </tr>
    <tr class="odd">
    <td><p>Location</p></td>
    <td><p>SharePoint</p></td>
    </tr>
    <tr class="even">
    <td><p>Archive directory</p></td>
    <td><p>Enter the URL for the SharePoint document library in this field. Be sure to include only the parts of the URL that are required. For example, don’t include “Allitems.aspx” at the end of the URL.</p></td>
    </tr>
    </tbody>
    </table>
    
    **For document templates**
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Class</p></td>
    <td><p>Template library</p></td>
    </tr>
    <tr class="even">
    <td><p>Group</p></td>
    <td><p>Document</p></td>
    </tr>
    <tr class="odd">
    <td><p>Location</p></td>
    <td><p>Archive directory</p></td>
    </tr>
    <tr class="even">
    <td><p>Archive directory</p></td>
    <td><p></p></td>
    </tr>
    <tr class="odd">
    <td><p>SharePoint site</p></td>
    <td><p>Enter the URL for the SharePoint site where the document templates are stored.</p>
    <p>Be sure to include only the parts of the URL that are required. For example, do not include “Allitems.aspx” at the end of the URL.</p></td>
    </tr>
    <tr class="even">
    <td><p>Document library</p></td>
    <td><p>Select the document library where the templates are stored.</p></td>
    </tr>
    </tbody>
    </table>
    
    For more information, see “Create a document type” in [Configure document management](configure-document-management.md).

## 3\. Attach a document to a record and save the document to a SharePoint document library

For record-keeping purposes, you might want all documents that you attach to Microsoft Dynamics AX records to also be saved to SharePoint document libraries. Instead of uploading the document to SharePoint first and then attaching it to a record, you can save record attachments to a SharePoint document library and attach them to a record at the same time.

To attach a document to a record and save the file to SharePoint at the same time, follow these steps:

1.  Open the record to attach a document to.

2.  On the **Action Pane**, click **Attachments**. Alternatively, click **File** \> **Command** \> **Document handling**.

3.  Click **New**, and then select the name of the document attachment document type that you created in step 2 of the Create document types for SharePointdocument libraries procedure earlier in this topic.

4.  Browse to the location of the file to attach, and then click **Open**.

## 4\. Save a document template to a SharePoint library and activate the template

Before you can use a template, you must save the template to a SharePoint library, and then activate the template in the **Document types** form.

To save a document template to a SharePoint library, follow these steps:

1.  Open a document template that you have already created. If you have not yet created document templates, see [Key tasks: Create and use a Word template by using the Office Add-ins](key-tasks-create-and-use-a-word-template-by-using-the-office-add-ins.md) or [Key tasks: Create and share an Excel template by using the Office Add-ins](key-tasks-create-and-share-an-excel-template-by-using-the-office-add-ins.md).

2.  Save the template to a SharePoint document library.

To activate a document template, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Select the document template document type that you created in the “Create document types for SharePoint document libraries” procedure earlier in this topic.

3.  On the **Document templates** FastTab, click **Synchronize**.

4.  Select the template to activate, and then click **Activate**.

## Related tasks

[Configure document management](configure-document-management.md)

## See also

[Document management](document-management.md)

  


