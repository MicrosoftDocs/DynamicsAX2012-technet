---
title: Install the RapidStart Connector
TOCTitle: Install the RapidStart Connector
ms:assetid: 26262a76-5b5c-4308-be11-4dcdc722bebe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh771574(v=AX.60)
ms:contentKeyID: 43881147
ms.date: 09/30/2015
mtps_version: v=AX.60
---

# Install the RapidStart Connector [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Beginning October 1, 2015, RapidStart services will no longer be supported. For more information, see the announcement on CustomerSourcehttps://mbs.microsoft.com/partnersource/northamerica/news-events/news/RapidStartServicesDiscontinued or PartnerSourcehttps://mbs.microsoft.com/customersource/northamerica/news-events/news-events/news/RapidStartServicesDiscontinued.

The Rapid Start Connector for Microsoft Dynamics AX enables RapidStart Services for Microsoft Dynamics ERP to communicate with an on-premise Microsoft Dynamics AX implementation.


> [!NOTE]
> <P>The RapidStart Connector is available through the Microsoft Dynamics AX Setup wizard in Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 Feature Pack.</P>



RapidStart Services is an online service that provides a questionnaire-based framework to configure and set up Microsoft Dynamics ERP products. This service is extensible and customizable to fit the business processes that must be configured. For more information about RapidStart Services, see <http://www.dynamicsonline.com>.

Install the RapidStart Connector on the server where the Application Object Server (AOS) is installed.

## Before you install the RapidStart Connector

  - Register your organization for RapidStart Services. Contact your partner or register yourself through <http://www.dynamicsonline.com>.

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - Create a domain account to use for the RapidStart Connector Windows service. For more information, see [Create service accounts](create-service-accounts.md).

## Install the RapidStart Connector

Use this procedure to install the RapidStart Connector. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Modify Microsoft Dynamics AX installation** page, click **Add or modify components**, and then click **Next**.

5.  On the **Add or modify components** page, select **RapidStart Connector**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Microsoft Dynamics ERP RapidStart Connector** page, enter the domain user account for the RapidStart Connector Windows service, and then click **Next**.

8.  On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

9.  On the **Ready to install** page, click **Install**.

10. After the installation is completed, click **Finish** to close the wizard.

## After you install the RapidStart Connector

Additional configuration is required after you install the RapidStart Connector. For more information, see [Configure Projects for Microsoft Dynamics AX ERP - RapidStart Services](http://go.microsoft.com/fwlink/?linkid=238738).

For information about how to use RapidStart Services, see [Help for Microsoft Dynamics ERP RapidStart Services users](http://go.microsoft.com/fwlink/?linkid=225970).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

