---
title: Install the Retail Channel Configuration Utility (Retail Store Database Utility)
TOCTitle: Install the Retail Channel Configuration Utility (Retail Store Database Utility)
ms:assetid: 2ede58e8-3dbe-4aed-8107-aaadf2fae1a8
ms:mtpsurl: https://technet.microsoft.com/library/Hh575204(v=AX.60)
ms:contentKeyID: 39555338
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Install the Retail Channel Configuration Utility (Retail Store Database Utility) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Install the Retail Channel Configuration Utility on computers where you must create a channel database or configure a Retail POS connection to a channel database. A channel database may be created either on a stand-alone database server or on a POS computer.

This topic explains how to install the Retail Channel Configuration Utility by using the Setup wizard.


> [!NOTE]
> <P>Retail components are available only with Microsoft Dynamics AX 2012 R3, AX 2012 R2, and AX 2012 Feature Pack. In AX 2012 R2 and AX 2012 Feature Pack, Retail Channel Configuration Utility was called Retail Store Database Utility.</P>



The Retail Channel Configuration Utility can be used to complete the following tasks:

  - Configure Retail POS and Offline Sync Service

  - Create a channel database

  - Create or re-provision an offline database

## Before you install the Retail Channel Configuration Utility

  - On the computer where you plan to install this component, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377) .

  - Install [Microsoft Sync Framework hotfix 2703853](https://support.microsoft.com/kb/2703853) on all computers on which you install Retail POS or Retail Modern POS.
    

    > [!IMPORTANT]
    > <P>This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



## Install the Retail Channel Configuration Utility (AX 2012 R3)

Use this procedure to install the Retail Channel Configuration Utility for AX 2012 R3. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select an installation option** page, click **Microsoft Dynamics AX**, and then click **Next**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Retail Channel Configuration Utility**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Ready to install** page, click **Install**.

9.  After the installation is completed, click **Finish** to close the wizard.

## Install the Retail Store Database Utility (AX 2012 Feature Pack and AX 2012 R2)

Use this procedure to install the Retail Store Database Utility for AX 2012 Feature Pack or AX 2012 R2. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

5.  On the **Select components** page, select **Retail Store Database Utility**, and then click **Next**.

6.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

7.  On the **Configure Retail store databases and POS** page, select the check box if you want to create store databases and associate them with a POS system.
    
      - To create a store database, enter the name of the server where you want to create the database, and then enter a name for the new database.
        
        When creating a shared store database, do not enter anything in the **Offline database name** or **Offline server name** fields. After you have created the shared store database, you can open the Retail Store Database Utility to designate this database as an offline database, but you cannot perform both actions at the same time.
    
      - To create an offline database, enter the name of the server where you want to create the database, and then enter a name for the new database.
    
      - Enter POS identification information.
        

        > [!IMPORTANT]
        > <P>Dummy values are required in the <STRONG>Identification</STRONG> fields because of a known issue.</P>

        
        In the **Store ID** field, type the ID of the store that the POS terminal is associated with. The store record does not need to be created before you complete this step. However, the ID must match later when the record is created and the profile is linked.
        
        In the **Terminal ID** field, type a unique ID for the POS terminal. The terminal ID that you enter must be listed in the POS terminals form.
        
        In the **Company** field, type the applicable company code.

8.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

9.  On the **Ready to install** page, click **Install**.

10. After the installation is completed, click **Finish** to close the wizard.

## After you install the Retail Channel Configuration Utility

For information about how to use the Retail Channel Configuration Utility, see the following topics:

  - [Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md)

  - [Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md)

  - [Configure database connections for a POS register by using the Retail Channel Configuration Utility](configure-database-connections-for-a-pos-register-by-using-the-retail-channel-configuration-utility.md)

  


