---
title: Configure Retail Modern POS for direct database connectivity
TOCTitle: Configure Retail Modern POS for direct database connectivity
ms:assetid: cba36c76-a44a-4a62-90c1-702e5930df86
ms:mtpsurl: https://technet.microsoft.com/library/Dn934706(v=AX.60)
ms:contentKeyID: 65218453
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure Retail Modern POS for direct database connectivity 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This topic explains how to configure direct database connectivity for Retail Modern POS by using the Retail Channel Configuration Utility.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to AX 2012 R3 Cumulative Update 8.</P>



Retail Modern POS can be configured to connect to a channel database either directly or through Retail Server. Offline mode is supported for both deployment options. For more information about supported deployment topologies, see [Retail Modern POS architecture](retail-modern-pos-architecture.md).

On each device where you want to configure direct database connectivity, you must use the Microsoft Dynamics AX Setup wizard to install the Retail Channel Configuration Utility. For more information, see [Install the Retail Channel Configuration Utility (Retail Store Database Utility)](install-the-retail-channel-configuration-utility-retail-store-database-utility.md).

The procedures in this topic assume that you have installed a supported version of Microsoft SQL Server on the computer where you plan to run the Retail Channel Configuration Utility. For a list of supported operating systems and SQL Server versions, see the [Microsoft Dynamics AX system requirements](https://go.microsoft.com/fwlink/?linkid=165377). For information about how to configure SQL Server for channel databases and offline databases, see [Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md).


> [!NOTE]
> <P>For direct database connections to work, you must configure direct database connectivity and set the appropriate point of sale (POS) user permissions.</P>
> <P>Additionally, if you are changing a previously activated instance of Retail Modern POS so that it uses a direct database connection, you must restart dllhost.exe from Task Manager.</P>



## Configure direct database connectivity for Retail Modern POS

1.  On a Retail Modern POS device, start the Retail Channel Configuration Utility.

2.  Click **Configure Retail Modern POS**.

3.  In the **Identification** section of the form, complete the information in the following fields:
    
      - **Store ID**: Enter the ID of the store that the POS register is associated with. The store must be listed in the **Retail stores form** in AX 2012 R3. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)
    
      - **Register ID**: Type a unique ID for the POS register. The POS register must be listed in the **POS registers** form in AX 2012 R3. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)

4.  In the **Channel Database** section of the form, select **Direct database connection**, and then complete the information in the following fields:
    
      - **Server name**: Select or type the name of the server that hosts the channel database.
    
      - **Database name**: Type the name of an existing channel database.

5.  Optional: Test the connection.

6.  Click **Apply** to finish the configuration.

## Configure POS user permissions for Retail Modern POS

1.  On a Retail Modern POS device, start the Retail Channel Configuration Utility.

2.  Click **Configure POS user permissions**.

3.  In the **POS User Configuration** section of the form, enter the Windows user name of the account that Retail Modern POS should run as.

4.  Click **Provide permission**.
    
    The account is added to the POS user group. For more information, see [Set up user accounts and the POS user group](set-up-user-accounts-and-the-pos-user-group.md).

  


