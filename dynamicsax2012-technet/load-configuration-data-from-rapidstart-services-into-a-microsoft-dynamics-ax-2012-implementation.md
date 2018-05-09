---
title: Load configuration data from RapidStart Services into a Microsoft Dynamics AX 2012 implementation
TOCTitle: Load configuration data from RapidStart Services into a Microsoft Dynamics AX 2012 implementation
ms:assetid: 77a09159-b04e-4159-85db-9e10618a1d94
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn193997(v=AX.60)
ms:contentKeyID: 52348251
ms.date: 09/18/2015
mtps_version: v=AX.60
f1_keywords:
- configure
- RapidStart
- configuration data
- Load configuration
---

# Load configuration data from RapidStart Services into a Microsoft Dynamics AX 2012 implementation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

As the Customer administrator for a Microsoft Dynamics ERP RapidStart Services project, you can load the configuration data that is collected in the project to your implementation of Microsoft Dynamics AX 2012. Before you can load the data, the following prerequisites must be met:

  - The Microsoft Dynamics ERP RapidStart Connector must be installed on Microsoft Dynamics AX. For more information, see [Install the Microsoft Dynamics ERP RapidStart Connector for RapidStart Services](install-the-microsoft-dynamics-erp-rapidstart-connector-for-rapidstart-services.md).

  - The implementation of Microsoft Dynamics AX that you want to load configuration data into must be registered as an endpoint in your RapidStart Services account. For more information, see [Register a Microsoft Dynamics ERP endpoint in RapidStart Services](register-a-microsoft-dynamics-erp-endpoint-in-rapidstart-services.md).

  - All the questions that are included in the configuration project must be answered.

<!-- end list -->

1.  In your browser, open online services for Microsoft Dynamics ERP at [http://www.dynamicsonline.com](http://go.microsoft.com/fwlink/p/?linkid=141031).

2.  Click **For Customers**, and then click **Sign in**.

3.  Sign in by using the Microsoft account (formerly Windows Live ID) that is associated with your customer account in online services.

4.  If your logon credentials are associated with more than one organization in RapidStart Services, on the **Choose your organization** page, click the name of the organization to work with.

5.  On the Customer Portal dashboard, click **Microsoft Dynamics® RapidStart**.

6.  In the main area of the **Getting started** page, click **Open an existing project**.

7.  On the **Projects** page, click the row of the configuration project from which to load data into Microsoft Dynamics AX.

8.  Click **Load into Microsoft Dynamics ERP**.

9.  On the **Connection parameters** page, in the **Target Microsoft Dynamics ERP implementation** list, select the server that you have registered as an endpoint for this configuration.
    
    RapidStart Services tests the connection to Microsoft Dynamics AX.

10. If more than one company is installed on the target server that hosts the instance of Microsoft Dynamics AX Application Object Server (AOS), in the **Company** list, select the identifier of the company.

11. Click **Load**.
    
    The load process may require a long time, depending on the volume of configuration data.
    
    After the load has been completed, a **Load results** page is displayed. This page includes a process summary that you can open in Microsoft Excel.
    
    The process summary includes information about any errors that occurred during the load process. This information can help you troubleshoot the issues that caused those errors.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

