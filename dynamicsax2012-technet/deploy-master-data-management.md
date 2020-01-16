---
title: Deploy Master Data Management
TOCTitle: Deploy Master Data Management
ms:assetid: c15ae977-07d6-43c9-8fbf-3ce9f7434377
ms:mtpsurl: https://technet.microsoft.com/library/Dn720449(v=AX.60)
ms:contentKeyID: 62224155
author: Khairunj
ms.date: 11/26/2014
mtps_version: v=AX.60
---

# Deploy Master Data Management 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic helps you deploy and run a baseline implementation of Microsoft Dynamics AX 2012 R3 Master Data Management (MDM).

## Prepare for Installation

Based on your business processes, determine whether your MDM configuration should be a multi-master or single-master environment. In a multi-master environment, multiple spokes can update master data. In a single-master environment, only one spoke can update data, whereas the other spokes just subscribe to the data. The type of environment affects the permissions that you have to set up when you configure accounts for access between the components. For more information, see [Configure Master Data Management](configure-master-data-management.md).

Next, determine whether you must manually de-duplicate data before you deploy MDM.

  - If all your AX 2012 R3 instances use the same natural key to identify a unique record, you do not have to do anything. For example, you have three instances, all of which contain records for Contoso Entertainment. In all three instances, the account ID for these records is CONENT. In this case, any conflict between records that have the same key but that are from different instances is identified after the first series of synchronizations with Microsoft SQL Server Master Data Services (SQL MDS).

  - If the keys that identify the same unique record differ across instances, you must decide whether de-duplication is required. For example, you have three AX 2012 R3 instances, all of which contain records for Contoso Entertainment. However, the account ID for these records differs in each instance: CONENT, Contoso, and CE1234. Depending on the requirements of your business processes, you can do nothing and keep these records as separate records. Alternatively, you can update the account IDs across the instances, so that a single value is used. Neither MDM nor Microsoft Dynamics AX provides a feature for de-duplication or RecID replacement. Therefore, before you deploy MDM, you must plan how you want to de-duplicate or purge data.

## Install Required Software

Install SQL MDS, install or upgrade to AX 2012 R3, and install the Microsoft Dynamics AX 2012 Data Import/Export Framework.


> [!IMPORTANT]
> <P>If you are running AX 2012 R2, you can install hotfix 2995611 to use master data management. For more information, see <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2995611">KB 2995611: Master data management in Microsoft Dynamics AX 2012 R2</A>.</P>



## Install SQL MDS

Install SQL MDS by following the instructions in [Install Master Data Services](https://go.microsoft.com/fwlink/?linkid=393359%26clcid=0x409). To install SQL MDS, you must have a SQL Server user account that has administrative rights. Additionally, it is easier to configure access if this SQL Server user account maps to the service account that you plan to use for the Data Import/Export Framework, and if that service account maps to the service account for Microsoft Dynamics AX Application Object Server (AOS).

Follow all the instructions in the **Pre-Installation Tasks** and **Installation Operations** sections. Then follow the instructions for these tasks in the **Post-Installation Tasks** section:

  - Open Master Data Services Configuration Manager to complete post-installation operations.

  - Create a Master Data Services database.

  - Create a Master Data Manager web application.

  - Associate a Master Data Services database with a web application.

  - Optional: Configure Internet Explorer Enhanced Security. This task is required only if you are installing SQL MDS on a computer that runs Windows Server 2008 or Windows Server 2008 R2.

  - Install the Master Data Services Add-in for Microsoft Excel.

  - Install [Cumulative update package 9 for SQL Server 2012 Service Pack 1](https://go.microsoft.com/fwlink/?linkid=396424%26clcid=0x409).

  - If you want additional security, configure Secure Sockets Layer (SSL) on the instance of Internet Information Services (IIS) that hosts the SQL MDS web application.

## Install or Upgrade to AX 2012 R3

If you are creating new AX 2012 R3 instances, follow the instructions in [Install Microsoft Dynamics AX 2012](install-microsoft-dynamics-ax-2012.md).

If you are upgrading existing Microsoft Dynamics AX instances to AX 2012 R3, follow the instructions in [Upgrade to Microsoft Dynamics AX 2012](upgrade-to-microsoft-dynamics-ax-2012.md).

## Install the AX 2012 Data Import/Export Framework

Install the AX 2012 Data Import/Export Framework on all Microsoft Dynamics AX instances that will participate in MDM. Follow the instructions in [Install the Data import/export framework (AX 2012 R3)](install-the-data-import-export-framework-ax-2012-r3.md).

## Set Up MDM and SQL MDS

Each participating AX 2012 instance must be connected to and synchronized with the SQL MDS server. To set up your first AX 2012 instance, follow these steps.

1.  Set up the SQL MDS database.

2.  Enable change tracking on the databases in both SQL MDS and AX 2012.

3.  Add the Data Import/Export Framework service account to SQL MDS security.

4.  Connect to the SQL MDS server from AX 2012.

5.  Publish MDM-enabled entities to SQL MDS.

6.  Create a synchronization schedule for the published entities.

This procedure gets the first AX 2012 instance and the SQL MDS database up and running. For subsequent AX 2012 instances, you can skip step 1. Then, in step 2, you have to enable change tracking only on the AX 2012 database.

## Set Up the SQL MDS Database

AX 2012 provides a Windows PowerShell cmdlet, **AXMasterDataManagementMDSSetup**, that simplifies setup of the SQL MDS database. The cmdlet adds the tables, stored procedures, and roles that MDM requires to the SQL MDS database. Follow these steps to run the cmdlet.

1.  Open Microsoft Dynamics AX Management Shell by going to **Start** \> **All Programs** \> **Administrative Tools** and then clicking **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, type the following command, and then press ENTER:
    
    Set-AXMasterDataManagementMDSSetup –MDSServerName \<SQL MDS server name\> -MDSDatabase \<SQL MDS database name\>
    

    > [!WARNING]
    > <P>If the network is slow, and this command times out, run the script by using a connection string parameter instead. Increase the connection time-out to 30 seconds or longer:</P>
    > <P>Set-AXMasterDataManagementMDSSetup -ConnectionString "Server=&lt;SQL MDS server name&gt;;Database=&lt;SQL MDS database name&gt;;Trusted_Connection=True;Connection Timeout=30"</P>



## Enable Change Tracking

You must enable change tracking on both the SQL MDS database and the AX 2012 business database. Open SQL Server Management Studio, connect to the SQL MDS database, and run the ALTER DATABASE command:

ALTER DATABASE \<SQL MDS database name\> SET CHANGE\_TRACKING=ON (CHANGE\_RETENTION = \<retention period\>)

The retention period is the amount of time that change tracking information is kept in the database. The value can be specified in days, hours, or minutes – for example:

ALTER DATABASE ContosoMBS SET CHANGE\_TRACKING=ON (CHANGE\_RETENTION = 60 days)

You should set the retention period on each server, and the value that you set should be based on the frequency with which you intend to sync data. In this way, you help guarantee that the tracking information is available for the synchronization operation.

Next, connect to the AX 2012 business database, and run the same T-SQL command against that database:

ALTER DATABASE \<Dynamics AX database name\> SET CHANGE\_TRACKING=ON (CHANGE\_RETENTION = \<retention period\>)

If change tracking is already enabled on the databases, make sure that the retention period that is configured meets your business requirements.

## Add the Service Account to SQL MDS

You must add the Data Import/Export Framework service account to the SQL MDS web service and database. Additionally, you must assign the service account permissions and roles that will enable it to perform MDM operations.

The Data Import/Export Framework service account requires access to the SQL MDS web service to push and pull data, and also to create schemas for AX 2012 entities. You should give the service account update permissions to each model in multi-master environments where you both pull and push data. You should give the service account read-only permissions to each model in single-master environments where you only pull data. To add the service account and assign it the required permissions, follow these steps.

1.  Open the SQL MDS web service.

2.  Click **Users and Group Permissions**.

3.  Add the Data Import/Export Framework service account.

4.  Select the Data Import/Export Framework service account that you just added, and then click **Edit**.

5.  Click the **Functions** tab, and then click **Edit** again.

6.  Assign the following functions to the user.
    
      - System Administration
    
      - Version Management
    
      - Integration Management

7.  Click **Save**.

The Data Import/Export Framework service account also requires access to the SQL MDS database to perform operations there. To assign the service account the required functions, open SQL Server Management Studio, connect to the SQL MDS database, and add the service account to the **axmdm\_exec** and **mds\_exec** roles.


> [!WARNING]
> <P>In a production environment with all entities configured, we recommend that you remove the permissions from the service account, and instead assign specific model permissions for reading and writing data to models.</P>
> <UL>
> <LI>
> <P>Assign Update permissions for each model in environments in which you both pull and push data.</P>
> <LI>
> <P>Assign Read-only permissions for each model in environment in which you only pull data.</P></LI></UL>



## Connect to the SQL MDS Server

Follow these steps to establish and verify a connection to the SQL MDS server.

1.  In AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **Configure SQL Server Master Data Services connection**.

3.  In the **Master Data Services connection** dialog box, enter the following information:
    
    1.  In the **Server** field, enter the name of the server where SQL MDS is installed.
    
    2.  In the **Repository** field, enter the name of the SQL MDS database.
    
    3.  In the **MDS service endpoint** field, enter the URL for the SQL MDS web service, followed by /service/service.svc. For example, enter http://ContosoMDSServer/MDS/service/service.svc.

4.  Click **Test configuration** to test the connection. If you cannot connect, verify the availability of the SQL MDS server and your connection information.


> [!NOTE]
> <P>If you receive an error when you test the connection, and you are sure about your connection information and server availability, the connection might be timing out before SQL MDS can respond. Try modifying the <STRONG>Server</STRONG> field value to &lt;SQL MDS server name&gt;;Connection Timeout=30.</P>



## Publish Entities to SQL MDS

The Data Import/Export Framework entities for Customers, Vendors, Employees, Global Address Book, and Products are preconfigured for use with MDM. You can decide to manage master data for some or all of these entities. To manage master data in other entities, see [Add an Entity to Master Data Management](add-an-entity-to-master-data-management.md).

To publish an MDM-enabled entity to SQL MDS, follow these steps.

1.  In AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **Publish entities to SQL Master Data Services**.

3.  In the **Publish entities to SQL Server Master Data Services** dialog box, select the entities to publish to SQL MDS, and then click **Create schema**.

4.  After the schema has been created, open the SQL MDS web application, and verify that models for the selected entities appear in the **Model** field.

## Configure Synchronization for Published Entities

After you have published the entities that you want to use to SQL MDS, you must configure synchronization for them. For more information, see the “Configure Synchronization” procedure in [Configure Master Data Management](configure-master-data-management.md).

## See also

[Configure Master Data Management](configure-master-data-management.md)

[Add an Entity to Master Data Management](add-an-entity-to-master-data-management.md)

  


