---
title: (RUS) About the transfer and maintenance of electronic documents
TOCTitle: (RUS) About the transfer and maintenance of electronic documents
ms:assetid: dd38e1c5-fecd-4906-adde-a2c6113eff02
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ735281(v=AX.60)
ms:contentKeyID: 49693282
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) About the transfer and maintenance of electronic documents [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX is integrated with a service provider for electronic document management to facilitate the transfer of statutory electronic documents to the reporting authorities, such as state tax services and state pension services. This integration provides follow-up services, such as document delivery confirmation and information about the approval status of the document. It also verifies the electronic documents and then converts them to a valid XML format.

After you have generated an electronic document that is ready to be transferred to the state tax services, you can save the document to an export folder that you can specify in the **Configuration of electronic document sending service** form. The documents that you save in the export folder are sent to a server for processing and validation. The validated documents can then be sent to the state tax services for approval.

When the status of the exported electronic document changes, the service detects the change and updates the status of the document in Microsoft Dynamics AX.


> [!NOTE]
> <P>You should receive information and instructions to install the required service provider applications after you complete a registration agreement with the service provider for electronic document management.</P>



## Prerequisites

The following prerequisites must be met before you can export electronic documents by using the electronic document management service:

  - Install the electronic document management service provider application that is required to validate and export the documents to the reporting authorities. After you install the application, you can configure settings for exporting electronic documents.

  - Install and choose a client digital certificate for the electronic documents.

  - Install a cryptographic service provider (CSP) application to encrypt the document data when you export electronic documents.

## See also

[(RUS) Set up folders to save exported electronic documents to and store the statuses of reports](rus-set-up-folders-to-save-exported-electronic-documents-to-and-store-the-statuses-of-reports.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

