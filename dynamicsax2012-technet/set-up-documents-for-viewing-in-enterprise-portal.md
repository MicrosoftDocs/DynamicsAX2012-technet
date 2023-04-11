---
title: Set up documents for viewing in Enterprise Portal
TOCTitle: Set up documents for viewing in Enterprise Portal
ms:assetid: 3df198cd-7d4a-4214-a4ef-3ef9cc995f8c
ms:mtpsurl: https://technet.microsoft.com/library/Dd309650(v=AX.60)
ms:contentKeyID: 35132611
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up documents for viewing in Enterprise Portal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, Enterprise Portal for Microsoft Dynamics AX does not display any documents. To view documents, you must map document types to document categories. Document categories determine the types of documents that can be displayed on specific Enterprise Portal module sites. The list of document categories is fixed, but the categories are general enough that they can accommodate most document types.

For example, if your organization uses Microsoft Visio diagrams, you must map the .vsd document type to a document category in Enterprise Portal. If the .vsd document type is not mapped to a category, users cannot view Visio diagrams in Enterprise Portal.

After you map document types to document categories, you must specify which document categories are visible on each Enterprise Portal module site, and which document categories are visible to external users. Document categories act as a kind of filter. Only users who have the appropriate permissions can view certain types of documents, and only on the designated module site.


> [!NOTE]
> <P>This topic does not describe how to add new document types to Microsoft Dynamics AX. For information about how to add new document types, and how to perform other document management tasks, see <A href="using-document-management.md">Using document management</A> in the Microsoft Dynamics AX online Help.</P>



## Before you begin

Enterprise Portal has the following document requirements and restrictions:

  - The Enterprise Portal database is the recommended storage location for documents.

  - Enterprise Portal does not support storing files in their original location. This means that Enterprise Portal users cannot retrieve or store documents on their local computer.

  - For document archiving, the Application Object Server (AOS) service account requires Full Control permission to delete documents.

  - For document archiving, Enterprise Portal does not accept the **Ask for confirmation** option. The physical file will always be deleted if this option is selected.

  - Document archives can be stored on the local AOS if only one AOS is used. For AOS clusters, document archives must be stored in a directory that uses a Universal Naming Convention (UNC) path.

<!-- end list -->

1.  Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Enterprise Portal parameters**.

2.  Click **Documents**.

3.  Select the document type to be displayed in Enterprise Portal, and then select the document category to map the document type to.
    

    > [!NOTE]
    > <P>Use the <STRONG>Online customer</STRONG> and <STRONG>Online vendor</STRONG> options to specify which document categories can be viewed by external users. If you do not specify any document categories for these options, external users cannot view any documents in Enterprise Portal.</P>



4.  Click **Close**.

## See also

[Specify Enterprise Portal parameters](specify-enterprise-portal-parameters.md)

[Configuring Enterprise Portal](configuring-enterprise-portal.md)

  


