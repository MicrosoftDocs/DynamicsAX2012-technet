---
title: Document management
TOCTitle: Document management
ms:assetid: 75db94e4-f2b8-4760-8dd8-a779ac74dbb5
ms:mtpsurl: https://technet.microsoft.com/library/Dn606151(v=AX.60)
ms:contentKeyID: 61180074
author: tonyafehr
ms.date: 09/17/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Document management 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic provides answers to common document management questions. You can use document management in Microsoft Dynamics AX to attach files to records. For example, you can attach PDF, Microsoft Word, or Microsoft Excel files to a purchase order or a sales order. You can also create Word and Excel templates from Microsoft Dynamics AX data.

## What is the difference between document handling and document management?

There is no difference. Both terms refer to the same functionality. In earlier versions of Microsoft Dynamics AX, the functionality was called document handling. In more recent versions, it’s called document management.

## What is the difference between document management and print management?

Document management lets you add notes, documents, and other files to records in Microsoft Dynamics AX.

Print management lets you control print settings for selected reports. Print settings include the number of copies, the printer destination, and the multilanguage text that can be included on the report. For more information, see [Print management](print-management.md).

## What is the difference between document types and file types?

Document types are used to categorize the documents that you attach to records or the templates that you create. The document management system handles several types of documents. These include letters, worksheets, and notes. Before you can create templates or attach documents to records, you must configure document types in the **Document types** form. For more information, see [Configure document management](configure-document-management.md).

A file type is the extension of the document. For example, .doc, .xlsx, and .pdf are all file types.

## Can I export or import document types?

Yes. For more information, see [Export and import a document type](export-and-import-a-document-type.md).

## Does document management integrate with Office 365?

Yes. Document attachments can be located anywhere on the Internet or on an intranet and can be attached by using the URL DocuType. For example, if you attach a Word document that is located on SharePoint Online to a record, the attachment opens in the web version of Word

## Can I store Microsoft Dynamics AX attachments in SharePoint?

Yes, but only if you’re using Microsoft Dynamics AX 2012 R2 or later. For more information, see [Configure and use Microsoft Dynamics AX document management with Microsoft SharePoint document libraries](configure-and-use-microsoft-dynamics-ax-document-management-with-microsoft-sharepoint-document-libraries.md).

## Can I use templates that are stored in SharePoint as Microsoft Dynamics AX document templates?

Yes, but only if you’re using AX 2012 R2 or later. For more information, see [Configure and use Microsoft Dynamics AX document management with Microsoft SharePoint document libraries](configure-and-use-microsoft-dynamics-ax-document-management-with-microsoft-sharepoint-document-libraries.md).

## Can I move a document archive?

Yes. However, you must copy the documents from the old archive to the new archive before you enter the new location in the archive directory field. This precaution is necessary so that you don’t break existing document references to existing documents.

To move a document archive, follow these steps:

1.  Copy all documents from the old archive to the new archive.

2.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document management parameters**.

3.  In the **General** area of the form, in the **Archive directory** field, enter the path of the new document archive.

## Why can’t I click the attachments icon in the Document handling form?

The attachments icon is available only if all of the following scenarios are true:

  - You have selected a record.

  - You have activated document management. For more information, see [Configure document management](configure-document-management.md).

  - You have permission to view attachments for the record.

## How do I lock the Document handling form?

The **Document handling** form always lists the documents that are attached to the selected record. If you leave the **Document handling** form open and you select another record, the form is updated to list the documents that are attached to the newly opened record.

To avoid updating the **Document handling** form when you select a different record, you can lock the view so that the information in the form doesn’t change.

To lock the **Document handling** form view, follow these steps:

1.  Select a record.

2.  Click **File** \> **Command** \> **Document handling** to open the **Document handling** form.

3.  Click **Functions** \> **Lock**.

4.  Select another record. The documents for the locked record are still displayed in the **Document handling** form.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Configure document management](configure-document-management.md)

[Key tasks: Create and use a Word template by using the Office Add-ins](key-tasks-create-and-use-a-word-template-by-using-the-office-add-ins.md)

[Key tasks: Create and share an Excel template by using the Office Add-ins](key-tasks-create-and-share-an-excel-template-by-using-the-office-add-ins.md)

  


