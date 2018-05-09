---
title: Configure database connections for a POS register by using the Retail Channel Configuration Utility
TOCTitle: Configure database connections for a POS register
ms:assetid: ab65600e-155a-4d63-971f-84e71d1aea79
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679928(v=AX.60)
ms:contentKeyID: 49557910
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure database connections for a POS register by using the Retail Channel Configuration Utility 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Retail Channel Configuration Utility (formerly named Retail Store Database Utility) can be used to configure database connections for a point of sale (POS) or Retail Modern POS register. This utility can also be used to install both a channel database and a POS register on the same computer, so that the database and register can be used in a development environment.

You must install the Retail Channel Configuration Utility on each computer where you want to use it. Use the Setup wizard for Microsoft Dynamics AX to install the utility. For more information, see [Install the Retail Channel Configuration Utility (Retail Store Database Utility)](install-the-retail-channel-configuration-utility-retail-store-database-utility.md).

The procedures in this topic assume that you have installed a supported version of Microsoft SQL Server on the computer where you plan to run the Retail Channel Configuration Utility. For a list of operating systems and SQL Server versions that are supported, see the [Microsoft Dynamics AX system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

The Retail Channel Configuration Utility can also be used to install a channel database on a shared database server or an offline database on a POS computer. For more information, see [Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md) or [Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md).

## Configure a database connection for a POS register (AX 2012 R3)

Complete the following procedure to configure the channel database connection for a POS register. To log on to Microsoft Dynamics AX for Retail POS, the register must have access to the channel database.

For information about additional parameters for POS registers, see [Set up registers](set-up-registers.md).

1.  On a POS computer, start the Retail Channel Configuration Utility.

2.  Click **Configure Retail POS and Retail Offline Sync Service**.

3.  In the **Identification** section of the form, complete the information in the following fields:
    
      - **Store ID** – Type the ID of the store that the POS register is associated with. The store must be listed in the **Retail stores** form. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)
    
      - **Register ID** – Type a unique ID for the POS register. The POS register must be listed in the **POS registers** form. (Click **Retail** \> **Setup** \> **POS** \> **POS registers**.)
    
      - **Legal entity** – Type the applicable company code.

4.  In the **Channel database** section of the form, complete the information in the following fields:
    
      - **Server name** – Select or type the name of the server that hosts the channel database.
    
      - **Database name** – Type the name of an existing channel database.

5.  Optional: Test the connection.

6.  Click **Apply** to configure the POS register.

## Configure a POS register without an offline database (AX 2012 R2)

Complete the following procedure to configure the database connections for a POS register that doesn’t include an offline database. To log on to Microsoft Dynamics AX for Retail POS, the register must have access to the store database.

For information about additional parameters for POS registers, see [Set up registers](set-up-registers.md).

1.  On a POS computer, click **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Retail Database Utility** \> **Retail Database Utility** to open the **Retail POS configuration** form.

2.  In the **Database** section of the form, select **Configure store database**. Complete the information in the following fields:
    
      - **Store server name** – Select or type the name of the server that hosts the store database.
    
      - **Store database name** – Type the name of an existing store database.

3.  Optional: Test the connection.

4.  In the **Database** section of the form, select **Configure offline database**.

5.  In the **Identification** section of the form, complete the information in the following fields:
    
      - **Store ID** – Type the ID of the store that the POS register is associated with. The store must be listed in the **Retail stores** form. (Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.)
    
      - **Register ID** – Type a unique ID for the POS register. The POS register must be listed in the **POS registers** form. (Click **Retail** \> **Setup** \> **POS** \> **POS registers**.)
    
      - **Data area ID** – Type the applicable company code.

6.  In the **Offline database** section of the form, leave the fields blank.

7.  Click **Continue** to configure the POS register.

## Configure a channel database and a POS register on a single computer

You can install Retail components on a single computer for development. In this case, you must run the Retail Channel Configuration Utility two times, in the following order, to install both a channel database and a POS register.

1.  In AX 2012 R3, create the channel database as described in the topic [Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md). In AX 2012 R2, create the store database as described in the topic [Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md).

2.  Configure the POS register, as described earlier in this topic.

## See also

[Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

