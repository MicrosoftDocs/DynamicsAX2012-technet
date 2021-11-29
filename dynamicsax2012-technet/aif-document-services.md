---
title: AIF Document Services
TOCTitle: AIF Document Services
ms:assetid: 783b3ed1-f5ee-44a0-88c2-8654f9bd2998
ms:mtpsurl: https://technet.microsoft.com/library/Bb496530(v=AX.60)
ms:contentKeyID: 35246007
author: Khairunj
ms.author: daxcpft
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# AIF Document Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Application Integration Framework (AIF), data can be exchanged with external systems through business logic exposed as services. Microsoft Dynamics AX includes services that are based on documents. A document is created by using XML, including header information that is added to create a message that can be transferred into or out of Microsoft Dynamics AX. Examples of documents include sales orders and purchase orders. However, almost any entity can be represented by a document, for example a customer. Services that are based on documents use the Axd \<Document\> classes that are included with Microsoft Dynamics AX. Collectively, these services are called document services.

Each document service exposes service operations that can be called by an external system and can take one or more documents as a parameter.

## XML Document Framework

The programmatic foundation of documents is the XML Document Framework. This framework consists of the classes that implement the business logic for individual documents in Microsoft Dynamics AX. The XML Document Framework contains the following types of classes:

  - Document service classes

  - Axd \<Document\> classes (also known as an Axd class)

  - Ax \<Table\> classes

In Microsoft Dynamics AX, all data is stored in database tables. A close relationship exists between the data model and the way that data is manipulated through forms and presented in reports. Therefore, an application that exchanges data with Microsoft Dynamics AX must be based on a detailed understanding of the data model, as well as any business logic applied in forms and reports, in order to maintain data consistency and integrity in the database.

To help to solve this problem, the document service classes expose service operations, which include create, delete, find, findKeys, getKeys, getChangedKeys, read, and update, and provide an application programming interface. The document service classes represent data as business entities so that the calling application can exchange data with Microsoft Dynamics AX without any knowledge of the underlying tables. The document services call functionality in the Axd \<Document\> classes.

The Axd \<Document\> classes contain the business logic for related entities. For example, the AxdSalesOrder class contains the logic for creating, updating, and deleting a sales order.

The Ax \<Table\> classes are a further abstraction of a table and encapsulate the business logic associated with creation and modification of records in the database tables. The Axd \<Document\> classes use the Ax \<Table\> classes to manipulate data in the database. The following figure illustrates how the Axd \<Document\> and Ax \<Table\> classes interact in a document exchange.

![XML Document Framework](images/Bb496530.XMLDocumentFramework(AX.60).gif "XML Document Framework")

**The Microsoft Dynamics AX classes in the XML Document Framework.**

For more information about these classes, see [Document Services Classes](document-services-classes.md).

The XML Document Framework classes are the basis of the document services that come with Microsoft Dynamics AX. You can use these document services without modification or customize them for your business requirements. For more information about the standard documents, see [Standard Document Services](standard-document-services.md).

The XML Document Framework also enables you to create new document services based on your own business logic. For more information, see [Creating New Document Services](creating-new-document-services.md).

The document services enable you to update data by using AIF. For more information, see [Updating Data With AIF](updating-data-with-aif.md).

## See also

[Using the Call Context](using-the-call-context.md)

