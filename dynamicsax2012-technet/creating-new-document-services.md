---
title: Creating New Document Services
TOCTitle: Creating New Document Services
ms:assetid: b18b02a2-7996-4d58-830a-4ade86329873
ms:mtpsurl: https://technet.microsoft.com/library/Aa856656(v=AX.60)
ms:contentKeyID: 35249740
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Creating New Document Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Application Integration Framework (AIF), a document exchange starts with a document (also called a [document class](document-services-classes.md)) that contains business logic. The document is serialized into the body of an XML message, and header information is added to create a message that can then be transferred into or out of Microsoft Dynamics AX. AIF includes out-of-the-box support for sending and receiving commonly used documents. For more information about the documents that ship with Microsoft Dynamics AX, see [Standard Document Services](standard-document-services.md).

In some cases, you might find that your business needs to exchange information with Microsoft Dynamics AX for which there is not an existing document service. In this case, you can use the extensible nature of AIF to create a custom document service to send and receive data. When you create a new service you also create a new document. For an example of creating a service, see [Walkthrough: Creating a Service by Using the AIF Document Service Wizard](walkthrough-creating-a-service-by-using-the-aif-document-service-wizard.md).

Consider the scenario in which your company needs to send some custom data to an external system for reporting. You also need to be able to receive data through AIF from an external accounting system.

If there is no existing document service to transfer data, a new service must be created in Microsoft Dynamics AX. The tool that is used to create a new document service is the **AIF Document Service Wizard**. The wizard creates all the necessary service and document components and alerts you to any best practices issues. Use the following steps to create a new document using the **AIF Document Service Wizard**:

1.  [Create the document query](how-to-create-a-document-query.md).

2.  [Run the AIF Document Service Wizard](how-to-create-a-service-by-using-the-aif-document-service-wizard.md).

3.  [Add any custom business logic to the document class](guidelines-for-adding-code-to-document-service-classes.md).

4.  Deploy the service for an inbound or outbound exchange.
    
    1.  If the document can be sent outbound (the service has read, find, findKeys, getKeys, or getChangedKeys service operations), you deploy the document service for an outbound exchange.
    
    2.  If the document can be received inbound (the service has create, update, or delete service operations), you deploy the document service for an inbound exchange.


> [!IMPORTANT]
> <P>Adding a custom document service requires in-depth knowledge of AIF and documents. Before creating a custom document in AIF, it is recommended that you configure an exchange with an existing document in order to become familiar with the way that document exchanges work in AIF. For more information, see <A href="walkthrough-exchanging-documents-by-using-the-file-system-adapter.md">Walkthrough: Exchanging documents by using the file system adapter</A>.</P>




> [!NOTE]
> <P>You must set permissions explicitly for any new query that uses the global address book (GAB) framework. A service that uses a newly-created query that references the GAB cannot use the automatic inference engine to set the permissions on the query.</P>



## See also

[How to: Create a Document Query](how-to-create-a-document-query.md)

