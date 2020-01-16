---
title: Register a Microsoft Dynamics ERP endpoint in RapidStart Services
TOCTitle: Register a Microsoft Dynamics ERP endpoint in RapidStart Services
ms:assetid: 134785ae-0d65-4641-a67d-6df2f5550d6b
ms:mtpsurl: https://technet.microsoft.com/library/Dn193985(v=AX.60)
ms:contentKeyID: 52348240
author: Khairunj
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- endpoint
- RapidStart
- register AOS
---

# Register a Microsoft Dynamics ERP endpoint in RapidStart Services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

You can create configuration projects in Microsoft Dynamics ERP RapidStart Services without a Microsoft Dynamics AX 2012 instance. However, before you can load a configuration project into Microsoft Dynamics AX Application Object Server (AOS) for a specific customer, the customer must install Microsoft Dynamics AX 2012 on the computer that is running the AOS instance. Then, you must register the AOS instance as an endpoint for RapidStart Services.

To load a configuration project from RapidStart Services to the AOS instance, Microsoft Dynamics ERP RapidStart Connector must be installed. For more information, see [Install the Microsoft Dynamics ERP RapidStart Connector for RapidStart Services](install-the-microsoft-dynamics-erp-rapidstart-connector-for-rapidstart-services.md).

To register an AOS endpoint, follow these steps:

1.  Open Microsoft Dynamics ERP RapidStart Connector from the **Start** menu.

2.  In the **Microsoft Dynamics ERP RapidStart Services Connector Settings** form, in the **Dynamics AX Service Host** field, enter the name of the computer that is running the AOS instance. The values in the remaining fields are added automatically. You can modify these values.

3.  Click **Activate** to start the Microsoft Dynamics ERP RapidStart Connector.
    
    The Microsoft Dynamics ERP RapidStart Connector is a standard Windows Server service. It may take the service some time to start, and in some cases, you may see a message reporting that the process has timed out, even though the service is still running. We recommend that you wait a few minutes before refreshing the service status to confirm that it has started. You can start the service manually as well.
    
    When activation is completed, an activation URL is displayed in the form.

4.  Click the link for the activation URL. You may be prompted for the credentials that you used to register for RapidStart Services. Select the service instance that is applicable for the target AOS instance, and then click **Submit**. The target AOS instance is also known as the endpoint.

5.  You receive the following message: **Endpoint updated successfully**. To verify the update, click **Manage endpoints**. The server name is listed in the **Target deployments** page of RapidStart Services.

## See also

[The architecture of the Microsoft Dynamics ERP RapidStart Connector](the-architecture-of-the-microsoft-dynamics-erp-rapidstart-connector.md)

  


