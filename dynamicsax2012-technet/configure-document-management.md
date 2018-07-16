---
title: Configure document management
TOCTitle: Configure document management
ms:assetid: 9fbb5573-9df5-4edd-925f-6b4ba6cbfcb1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn636897(v=AX.60)
ms:contentKeyID: 61223075
ms.date: 07/09/2014
mtps_version: v=AX.60
f1_keywords:
- document
- documents
- Forms.DocuType
- document handling
- document managament
- MsDynAx060.Forms.DocuType
---

# Configure document management 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to configure document management for the first time. You can use document management, also known as document handling, to attach notes, documents, or document references to records. You can also use Office Add-ins for Microsoft Dynamics AX to integrate with document management and create Microsoft Word and Microsoft Excel documents or document templates that use Microsoft Dynamics AX data.

The following illustration shows how to configure document management. The numbers correspond to the procedures later in this topic.

![The configure document management process](images/Dn636897.ConfigDM(AX.60).png "The configure document management process")

## 1\. Activate document management

Before you can attach documents to records or generate documents from a record, you must activate the document management functionality and then you must activate document management for specific tables.

To activate document management, follow these steps:

1.  Click **File** \> **Tools** \> **Options**.

2.  In the **General** area, expand the **Miscellaneous** FastTab.

3.  In the **Document handling** field group, select the **Document handling active** check box.

To activate document management for specific tables, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Active document tables**.

2.  Click **New**.

3.  Select the name of the table to activate document management for.
    
    **Example**
    
    To activate document management for sales orders, select the SalesTable table name.

4.  Repeat steps 2 and 3 for each table that you want to activate document management for.

## 2\. Specify a document archive directory

When you attach a document to a record in Microsoft Dynamics AX, it is stored in a location that you specify. This location is called an archive directory. You can specify one archive directory for all the document types you set up, or you can specify a separate archive directory for each document type. If you don’t specify an archive directory for a document type, the document type uses the archive directory that you specify in this procedure. See “Create or import document types” later in this topic for more information about how to specify an archive directory for a document type.


> [!NOTE]
> <P>If you use Enterprise Portal for Microsoft Dynamics AX, there are additional requirements and restrictions about document archives. For more information, see <A href="set-up-documents-for-viewing-in-enterprise-portal.md">Set up documents for viewing in Enterprise Portal</A>.</P>



To specify a location for the Microsoft Dynamics AX document archive directory, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document management parameters**.

2.  In the **General** area, browse to the location of the archive directory.
    

    > [!WARNING]
    > <P>If you already have an archive directory specified and you want to change it, you first must move the contents of the existing archive directory to the new archive directory. For more information, see <A href="document-management.md">Document management</A>.</P>



3.  Optional: Specify the maximum file size that is allowed for documents.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Max. file size in database</strong></p></td>
    <td><p>Enter the maximum file size, in megabytes, for a file that is saved to the Microsoft Dynamics AX database.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Max. file size in file system</strong></p></td>
    <td><p>Enter the maximum file size, in megabytes, for a file that is saved to the archive directory location.</p></td>
    </tr>
    </tbody>
    </table>


## 3\. Specify number sequences for documents

Before you can use document management, you must specify number sequences for documents. The files that you attach to records are renamed when they are stored in the archive directory. The file name of the attached files is determined by the number sequences that you set up for documents.

To specify number sequences for documents, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document management parameters**.

2.  In the **Number sequences** area, select a number sequence code for each reference.
    
    If the number sequence code that you’re looking for is not listed, you must create a new number sequence code in the **Number sequences** list page. For more information, see [Set up number sequences](set-up-number-sequences.md).

## 4\. Specify file types

You can control which types of files, or documents that have specific file name extensions, that users can attach to Microsoft Dynamics AX records.

To specify file types, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document management parameters**.

2.  In the **File types** area, review the default file types. Remove the file types that users should not be able to attach to records, and add any additional file types that users should be able to attach to records.

## 5\. Optional: Configure integration with Office Add-ins

When you use document management, you can integrate with Office Add-ins to create Word documents and Excel workbooks that are linked dynamically to the tables in Microsoft Dynamics AX. For specific instructions about how to do this, see [Install Office Add-ins](install-office-add-ins.md) and [Set up integration with Microsoft Office Add-ins](set-up-integration-with-microsoft-office-add-ins.md).

## 6\. Create or import document types

Document types are required for document management and are used to categorize the documents that you attach to records. When you create an unattached document, one of these content types is assigned to it. If you have workflows set up, workflow uses the document type to route the document to the appropriate user or work-item queue.

The **Note** and **File** document types are available by default.

## Create document types

To create a document type, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Click **New**, and then enter the following information about the document type.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Class</strong></p></td>
    <td><p>Select the action that occurs when a user creates an attachment of the selected document type:</p>
    <ul>
    <li><p><strong>Attach URL</strong> – Attach a reference to a document by using a URL.</p></li>
    <li><p><strong>Create a Microsoft Excel worksheet by using COM</strong> – Create an Excel worksheet and copy data from the selected transaction.</p></li>
    <li><p><strong>Create a Microsoft Word document by using COM</strong> – Create a Word document and copy data from the selected transaction.</p></li>
    <li><p><strong>Create application document</strong> – Create a Word document without opening Word.</p></li>
    <li><p><strong>Simple note</strong> – Create a simple note for the referenced transaction.</p></li>
    <li><p><strong>Template library</strong> – Create a template file by using Word or Excel, and then save the file to a template library. For example, you can create a budget template by using Excel. Each department in your organization then enters budget information in a copy of the template.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>Your system administrator must create the site or SharePoint document library for the template library.</P>


    </div></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Group</strong></p></td>
    <td><p>Select the group for the document type.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Auto-save</strong></p></td>
    <td><p>Select this check box to automatically save temporary files to the database after you use them.</p>
    <p>Typically, temporary files are stored in the <strong>Temp</strong> folder in Microsoft Windows. To save temporary files in the directory that is specified in the <strong>File location</strong> list, select <strong>Auto-save</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Autodelete</strong></p></td>
    <td><p>Select this check box to automatically delete temporary files after you use them.</p>
    <p>Typically, temporary files are stored in the <strong>Temp</strong> folder in Windows.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Remove</strong></p></td>
    <td><p>Select <strong>Document only</strong> to remove only the reference to the document file or select <strong>Document and physical file</strong> to remove both the reference and the physical file.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Ask for confirmation</strong></p></td>
    <td><p>Select this check box to require confirmation before the physical file is deleted.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Category</strong></p></td>
    <td><p>Select an Enterprise Portal document category to associate with the document type.</p>
    <p>Details for document categories are set up in the <strong>Enterprise Portal parameters</strong> form. For more information, see <a href="attach-documents-notes-or-urls-to-records.md">Attach documents, notes, or URLs to records</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Archive directory</strong></p></td>
    <td><p>The directory where document files of the selected document type are stored.</p>
    <p>If this field is empty, the default archive directory that is specified in the <strong>Document management parameters</strong> form is used as the archive directory.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>If you use Enterprise Portal, there are additional requirements and restrictions about document archives. For more information, see <A href="set-up-documents-for-viewing-in-enterprise-portal.md">Set up documents for viewing in Enterprise Portal</A>.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Location</strong></p></td>
    <td><p>Select the location where document files for this content type are stored. The following options are available:</p>
    <ul>
    <li><p><strong>Archive directory</strong> – Documents of this type are stored in the directory that is specified in the <strong>Archive directory</strong> field.</p></li>
    <li><p><strong>Database</strong> – Documents of this type are stored in the Microsoft Dynamics AX database.</p></li>
    <li><p><strong>Original location</strong> – Documents of this type are stored in the location that was used when the file was originally attached to the record.</p></li>
    <li><p><strong>SharePoint</strong> – Documents of this type are stored in a SharePoint document library.</p></li>
    </ul>
    <div class="alert"> 

    > [!NOTE]
    > <P>If documents are stored in a shared location instead of the database, verify that the correct access level is set for the shared location.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Check table</strong></p></td>
    <td><p>If this check box is selected, the selected document type is available only from the tables that are specified in the <strong>Options</strong> form.</p>
    <p>By default, the check box is cleared for the standard document types, <strong>Note</strong> and <strong>File</strong>.</p>
    <p>For more information, see <a href="https://technet.microsoft.com/en-us/library/aa553828(v=ax.60)">Restrict a document type to a specific table</a>.</p></td>
    </tr>
    </tbody>
    </table>


## Import document types

To import document types, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Click **Import**.

3.  Browse to the location of the file that contains the exported document types.

4.  When prompted to delete tables before you import, click **Yes to all**, and then click **OK**.

5.  Click **Yes** to confirm.

## 6a. Optional: Configure document management for SharePoint

You can use SharePoint document libraries to store document attachments or document templates. For more information, see [Configure and use Microsoft Dynamics AX document management with Microsoft SharePoint document libraries](configure-and-use-microsoft-dynamics-ax-document-management-with-microsoft-sharepoint-document-libraries.md).

## 6b. If you use Enterprise Portal: Configure document categories

In Enterprise Portal, you can select the modules or product areas that display specific document categories and the kinds of external users who can open the documents.

To configure document categories in Enterprise Portal, see [Set up documents for viewing in Enterprise Portal](set-up-documents-for-viewing-in-enterprise-portal.md).

## 7\. Specify content types

Content types are used to categorize documents that are not attached to records. Examples of unattached documents might be invoices, expense reports, or purchase orders. Workflow uses document content types to route documents to the correct user or work-item queue for processing. For more information, see [Configuring the workflow system](configuring-the-workflow-system.md).

To create content types, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document content types**.

2.  Click **New**, and then enter a name and a description for the content type.

For more information, see [Document content types (form)](https://technet.microsoft.com/en-us/library/hh209674\(v=ax.60\)).

## 8\. Optional: Specify document management settings for AIF

Before you can use Application Integration Framework (AIF) document services, you must specify document management settings for AIF. AIF document services are query-based services that you can use to exchange data with external systems by sending and receiving XML documents. These documents represent business entities, such as customers, vendors, or sales orders.

To specify document management settings for AIF, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document management parameters**.

2.  Click **AIF**.

3.  Complete the following fields.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Document type:</strong></p></td>
<td><p>Select the document type for notes in incoming electronic documents. For sales orders, this type must be <strong>Note</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Document file service</strong></p></td>
<td><p>Select this check box if the web service document files should be submitted to workflow for routing to appropriate parties.</p></td>
</tr>
</tbody>
</table>


For more information, see [AIF Document Services](aif-document-services.md).

## Next step

After you have configured document management, you can attach documents to records or create document templates for specific document types. For more information, see [Create a note](create-a-note.md), [Create a document template and associate it with a document type](create-a-document-template-and-associate-it-with-a-document-type.md), or [Create a reference to an existing document](create-a-reference-to-an-existing-document.md).

Optionally, if you set up the integration with Office Add-ins, you can create Word documents and Excel workbooks that are linked dynamically to the tables in Microsoft Dynamics AX. For more information, see [Key tasks: Create and use a Word template by using the Office Add-ins](key-tasks-create-and-use-a-word-template-by-using-the-office-add-ins.md) or [Key tasks: Create and share an Excel template by using the Office Add-ins](key-tasks-create-and-share-an-excel-template-by-using-the-office-add-ins.md).

## Related tasks

[Copy a note or document reference](copy-a-note-or-document-reference.md)

## See also

[Document management in sales and marketing](document-management-in-sales-and-marketing.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

