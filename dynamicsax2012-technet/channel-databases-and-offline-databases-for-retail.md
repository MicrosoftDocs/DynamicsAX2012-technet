---
title: Channel databases and offline databases for Retail
TOCTitle: Channel databases and offline databases for Retail
ms:assetid: fdc21b0b-5587-41a4-8418-d10f9b5ab6ba
ms:mtpsurl: https://technet.microsoft.com/library/JJ679942(v=AX.60)
ms:contentKeyID: 49557924
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Channel databases and offline databases for Retail 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

When you implement Microsoft Dynamics AX 2012 for Retail, you create a database for each store location or online store. This database is called the *channel database*. A channel database holds only the data that is required for retail transactions.

For a brick-and-mortar store, the channel database is also known as a store database and is typically located on the premises. You can connect multiple point-of-sale (POS) computers to the same channel database to read and write data. This helps ensure that the same master data is available to all POS computers in a store.

If you’re using Retail POS, you can also create offline databases on POS computers. An offline database helps ensure that the store’s operations can continue even if the connection to the shared database server is lost. If the connection to the shared database server is lost, the POS computers switch to offline databases. The shared database and the offline databases are kept in sync by Microsoft Dynamics AX for Retail Offline Sync Service.

The following topics describe how to set up channel databases and offline databases for Retail:

[Configure SQL Server for the Retail databases](configure-sql-server-for-the-retail-databases.md)

[Install a Retail channel database](install-a-retail-channel-database.md)

[Install the Retail Channel Configuration Utility (Retail Store Database Utility)](install-the-retail-channel-configuration-utility-retail-store-database-utility.md)

[Create a channel database or an offline database (AX 2012 R3)](create-a-channel-database-or-an-offline-database-ax-2012-r3.md)

[Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)](create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md)

[Set up a channel database profile](set-up-a-channel-database-profile.md)

[Create a channel data group](create-a-channel-data-group.md)

[Set up a store database profile](set-up-a-store-database-profile.md)

[Set up offline profiles](set-up-offline-profiles.md)

  


