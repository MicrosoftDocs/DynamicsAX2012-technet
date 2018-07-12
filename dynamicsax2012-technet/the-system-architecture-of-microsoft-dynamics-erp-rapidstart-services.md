---
title: The system architecture of Microsoft Dynamics ERP RapidStart Services
TOCTitle: The system architecture of Microsoft Dynamics ERP RapidStart Services
ms:assetid: f17f421f-c52b-4f94-8108-41cb6c9d956c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn221773(v=AX.60)
ms:contentKeyID: 54161570
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- architecture
- Dynamics AX
- RapidStart
---

# The system architecture of Microsoft Dynamics ERP RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

Microsoft Dynamics ERP RapidStart Services is a cloud-based questionnaire that helps you configure an instance of Microsoft Dynamics AX 2012 for your organization. Use RapidStart Services to select parameter settings and enter master records for a customer’s installation of Microsoft Dynamics AX Application Object Server (AOS). For example, you can set up a chart of accounts for your customer, select payment methods, import customers and vendors, and import ZIP Codes or postal codes.

## Set up RapidStart Services architecture to configure Microsoft Dynamics AX 2012

After you register as a partner and activate your account in the Partner Portal for online services for Microsoft Dynamics ERP, your Microsoft account information is synchronized with RapidStart Services. You are automatically assigned as a RapidStart Services user for the customer name that you entered in the Partner Portal. Sign in to the Customer Portal for RapidStart Services to create, design, and administer a configuration project for the customer.

When you are ready to load a RapidStart Services configuration project for a Microsoft Dynamics AX 2012 customer, you must complete the following prerequisite tasks:

1.  On the same computer that is running the customer’s AOS instance, install Microsoft Dynamics ERP RapidStart Connector. Microsoft Dynamics ERP RapidStart Connector is a service that enables communication between a RapidStart Services instance and an AOS instance. For more information, see [Install the Microsoft Dynamics ERP RapidStart Connector for RapidStart Services](install-the-microsoft-dynamics-erp-rapidstart-connector-for-rapidstart-services.md).

2.  Register the AOS instance as the endpoint for the Microsoft Dynamics ERP RapidStart Connector instance. For more information, see [Register a Microsoft Dynamics ERP endpoint in RapidStart Services](register-a-microsoft-dynamics-erp-endpoint-in-rapidstart-services.md).

3.  Answer all the questions that are included in the configuration project. When all the sections in the configuration project are answered, load the data from RapidStart Services into the AOS instance that you registered as the endpoint for the Microsoft Dynamics ERP RapidStart Connector instance. For more information, see [Load configuration data from RapidStart Services into a Microsoft Dynamics AX 2012 implementation](load-configuration-data-from-rapidstart-services-into-a-microsoft-dynamics-ax-2012-implementation.md).

The following diagram illustrates the architecture of RapidStart Services that must be set up to use RapidStart Services to configure an instance of Microsoft Dynamics AX 2012.

![Action sequence load generator](images/Dn221773.RapidStartActionSequenceLoadGenerator(AX.60).jpg "Action sequence load generator")

## Try out RapidStart Services

Microsoft Dynamics Certified Partners can register to try RapidStart Services before they sign up their customers and prospects. Microsoft Dynamics Certified Partners can try RapidStart Services without installing the Microsoft Dynamics ERP RapidStart Connector or registering an AOS endpoint. For more information, see [Try out Microsoft Dynamics ERP RapidStart Services](try-out-microsoft-dynamics-erp-rapidstart-services.md).

## See also

[The architecture of the Microsoft Dynamics ERP RapidStart Connector](the-architecture-of-the-microsoft-dynamics-erp-rapidstart-connector.md)

[The load architecture of Microsoft Dynamics ERP RapidStart Services](the-load-architecture-of-microsoft-dynamics-erp-rapidstart-services.md)

  


