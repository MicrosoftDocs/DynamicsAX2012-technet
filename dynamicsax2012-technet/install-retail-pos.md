---
title: Install Retail POS
TOCTitle: Install Retail POS
ms:assetid: c95dfdc6-6136-48cc-9dc7-1c4f199f54d9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh575249(v=AX.60)
ms:contentKeyID: 39555412
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install Retail POS [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Retail POS is a component that is required for the day-to-day operation of Retail at a store. When you install the Retail POS component, the Retail Salt Utility is also installed. The Retail Salt Utility provides extra encryption for the passwords and credentials that are associated with the Retail system.


> [!NOTE]
> <P>Retail components are available with Microsoft Dynamics AX 2012 R3, AX 2012 R2, and AX 2012 Feature Pack.</P>



At the store, install this component on each register computer. If you plan to use a stand-alone database server at the store, you must also install Retail POS on the database server, even if Retail POS will not be used on that computer. This step is required to set up the database. Additionally, install Retail POS on a communications server if that computer will also be used to process transactions.

In AX 2012 R3, you can use the Retail mass deployment toolkit to deploy Retail POS to a large number of client computers. For more information, see [Mass deploy Retail components by using System Center Configuration Manager](mass-deploy-retail-components-by-using-system-center-configuration-manager.md).


> [!NOTE]
> <P>If you are upgrading Retail POS, you should review <A href="scenario-upgrade-a-retail-system.md">Scenario: Upgrade a Retail system</A>.</P>



## Before you install Retail POS

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - 
    

    > [!IMPORTANT]
    > <P>Install <A href="https://support.microsoft.com/kb/2703853">Microsoft Sync Framework hotfix 2703853</A> on all computers on which you install the Retail POS. This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



## Install Retail POS

Use this procedure to install Retail POS. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Retail POS**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Ready to install** page, click **Install**.

9.  After the installation is completed, click **Finish** to close the wizard.

## After you install Retail POS

1.  If an offline database is required, create and configure the offline database for each POS register by using the Retail Channel Configuration Utility. For more information, see [Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md) or [Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md).

2.  Configure Retail POS database connections by using the Retail Channel Configuration Utility. For more information, see [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md).

3.  Configure Retail POS for your business. For more information, see [Point of Sale](point-of-sale.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

