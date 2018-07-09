---
title: Create a reference to an unattached document
TOCTitle: Create a reference to an unattached document
ms:assetid: ae13a411-29a9-43dd-9bf8-a85412ba567e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242704(v=AX.60)
ms:contentKeyID: 36058937
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a reference to an unattached document [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Unattached documents are documents that are stored in an external location instead of in Microsoft Dynamics AX. Unattached documents can include a variety of content types, such as invoices, expense reports, or bank statements. Workflow uses the content type to route the document to the correct user or work-item queue.

## Create a reference to an unattached document

1.  Click **Home** \> **Common** \> **Document management** \> **Unattached documents**.

2.  In the **New document file** form, click **New**.

3.  In the **General** section of the form, select a content type and enter a file name.

4.  In the **Attributes** section of the form, locate the document on a server computer or enter the URL of the document, and then enter the date on which the document was received. For example, if the document was received via fax, enter the date on which the fax was received.
    

    > [!NOTE]
    > <P>If the unattached document is created by the document handling web service, the received date is set when the document is imported. Documents can be created by the document handling web service only if the service has been configured.</P>



5.  Enter comments about the document, if necessary.

## See also

[Unattached documents (form)](https://technet.microsoft.com/en-us/library/hh227648\(v=ax.60\))

[Document content types (form)](https://technet.microsoft.com/en-us/library/hh209674\(v=ax.60\))

[Create a document content type](create-a-document-content-type.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

