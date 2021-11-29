---
title: Document Services Classes
TOCTitle: Document Services Classes
ms:assetid: 58d95442-703d-4ef1-a4c4-9af0ef45b3a0
ms:mtpsurl: https://technet.microsoft.com/library/Aa606696(v=AX.60)
ms:contentKeyID: 35244339
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Document Services Classes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Application Integration Framework (AIF) a document is a representation of the data model in Microsoft Dynamics AX. This means that a document reflects the data as it occurs in the application. For example, the sales order document contains a sales order header with the sales order data and the corresponding sales order lines for a particular sales order. This document structure reflects the existing records in the application.

In most cases, the data fields that can be updated in the document are included on the form of the same name in the Microsoft Dynamics AX client. For example, to view the **Sales order** form, click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Viewing the records on the form also shows you what data is available to the read and find service operations for the AIF document service.

In AIF, data is exchanged in XML format. The AIF classes are responsible for serializing the data to or from XML for use by the transport layer. These classes include the document services classes, the Axd\<Document\> classes, and the Ax\<Table\> classes. The source of data for each document is a query (the Axd document query). The query controls the content and structure of the data in the document.

The topics in this section provide information about document services classes and document schemas.

[AIF Class Naming Conventions](aif-class-naming-conventions.md)

[About Document Service Classes](about-document-service-classes.md)

[About Axd\<Document\> Classes](about-axd-document-classes.md)

[About Ax\<Table\> Classes](about-ax-table-classes.md)

[Document Schemas](document-schemas.md)

[Document XML Generation](document-xml-generation.md)

[Document Class Service Operations](document-class-service-operations.md)

[How to: Update a Service After Adding a Query Data Source](how-to-update-a-service-after-adding-a-query-data-source.md)

[Record Level Security and Outbound Documents](record-level-security-and-outbound-documents.md)

