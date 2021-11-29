---
title: 'Install Commerce Data Exchange: Synch Service (Retail Store Connect)'
TOCTitle: 'Install Commerce Data Exchange: Synch Service (Retail Store Connect)'
ms:assetid: fe4c8504-6645-4952-a6bf-20f50fa984ea
ms:mtpsurl: https://technet.microsoft.com/library/Hh575262(v=AX.60)
ms:contentKeyID: 39555434
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install Commerce Data Exchange: Synch Service (Retail Store Connect) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Commerce Data Exchange: Synch Service is a service that shares data among retail components. These components include the head office, stores, and individual point of sale (POS) terminals. When you install Synch Service, the Retail Salt Utility is also installed. The Retail Salt Utility provides extra encryption for the passwords and credentials that are associated with the Retail system.


> [!NOTE]
> <P>Retail components are available with Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 Feature Pack. In AX 2012 Feature Pack, Synch Service is called Retail Store Connect.</P>
> <P>In AX 2012 R3, Synch Service has been replaced by Commerce Data Exchange: Async Server and Commerce Data Exchange: Async Client</P>
> <P>In AX 2012 R3, deploy this component only if you must support earlier versions of Microsoft Dynamics AX for Retail POS while you upgrade (N-1). For more information, see <A href="scenario-upgrade-a-retail-system.md">Scenario: Upgrade a Retail system</A>.</P>



To deploy Synch Service on multiple computers in an environment, you can run Setup on each computer.

## Before you install Synch Service

  - Determine how many instances of Synch Service you want to install, and on which computers.
    
    In a basic deployment of Retail, one instance of Synch Service is installed at the head office, and one instance is installed at each store. In this scenario, the head-office instance communicates with Microsoft Dynamics AX Application Object Server (AOS), and a store instance communicates with the store database.
    
    Operations in a large organization might scale more efficiently if you install multiple Synch Service instances at each site, either on a single server or on multiple servers. For more information, see [Run multiple instances of Synch Service](run-multiple-instances-of-synch-service.md).
    

    > [!WARNING]
    > <P>Although a single instance of Synch Service can manage all communications for the organization, excessive load or network latency might decrease performance.</P>

    
    If Retail Scheduler will be used on a Microsoft Dynamics AX client computer to run jobs and send data to stores, install Synch Service on the client system.

  - Determine whether you want to use Network Load Balancing (NLB) and Internet Protocol security (IPsec). Retail supports NLB for data that comes from the store to Microsoft Dynamics AX, but not for outgoing data. If you’re using multiple instances of Synch Service, NLB can distribute incoming data among them, but all instances must have the same service name. If IPsec is enabled, we recommend that you not use NLB.

  - Select a service account for the Synch Service service. For information about the requirements for service accounts, see [Create service accounts](create-service-accounts.md).

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - At the head office, .NET Business Connector must be installed on the same computer as Synch Service. Synch Service uses .NET Business Connector to communicate with AOS.

## Install Synch Service

Use this procedure to install Synch Service. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you’re installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, on the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Synch Service**, and then click **Next**.

7.  On the **Configure Commerce Data Exchange: Synch Service** page, select the check box to configure Synch Service by using Setup. If you clear this check box, the application files are installed, but Synch Service is not configured.
    
      - To create a message database for Synch Service, enter the name of the server on which to create the database, and then enter a name for the new database.
    
      - To configure the service account for Synch Service, enter a user name and password.
    
    If you want to change this information later or configure other settings, such as a port and a service name, you must use the Synch Service Settings Wizard. For more information, see [Configure settings for Synch Service](configure-settings-for-synch-service.md).

8.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

9.  On the **Ready to install** page, click **Install**.

10. After the installation is completed, click **Finish** to close the wizard.

  


