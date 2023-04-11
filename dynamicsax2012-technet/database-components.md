---
title: Database components
TOCTitle: Database components
ms:assetid: 7721376c-08b6-443d-9e27-b575f5f461bf
ms:mtpsurl: https://technet.microsoft.com/library/Gg731834(v=AX.60)
ms:contentKeyID: 35132683
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Database components 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX relies on two Microsoft SQL Server databases, the business database and the model store database. During upgrade, an additional database, the baseline model store, is used. This topic provides an overview of the databases and the types of tables that each database stores.


> [!IMPORTANT]
> <P>In Microsoft Dynamics AX 2012 R2, the model store was moved into a database that is separate from the business database.</P>



The Microsoft Dynamics AX business database contains two primary types of tables:

  - Tables that can be accessed from the data dictionary in the Application Object Tree (AOT).

  - Kernel tables that can be accessed from the **System Documentation** section of the AOT. Kernel tables are used by Microsoft Dynamics AX. These tables are not associated with table groups, and cannot be directly imported, exported, or changed.

The model store is the database where all application elements for Microsoft Dynamics AX are stored. Customizations are also stored in the model store. The model store replaces the Application Object Data (AOD) files that were used in earlier versions of Microsoft Dynamics AX.

The name of the model store consists of the name of the business database plus **\_model**. Both the business database and the model store database must be hosted on the same database server and the same instance of SQL Server. The model store database holds model store tables that can be accessed from the **System Documentation** section of the AOT. These tables cannot be directly imported, exported, or changed. For more information, see [Model store architecture](model-store-architecture.md).

The model store can be managed by using the AXUtil command-line utility or Windows PowerShell. In Microsoft Dynamics AX, the model store tables are visible in the AOT, in the **System Documentation** \> **Tables** \> **SysModel\*** section.

The baseline model store holds model store tables for the earlier version of the metadata and is used only during upgrade. The baseline model store is like the **old** folder in earlier versions of Microsoft Dynamics AX.

## Tables that can be accessed from the data dictionary

The tables that can be accessed from the data dictionary in the AOT include tables in the following table groups:

  - **Framework** – Includes tables that are used by underlying Microsoft Dynamics AX frameworks, such as Application Integration Framework (AIF). These tables are created during installation and are not associated with configuration keys.

  - **Group** – Includes tables that are used to categorize the tables in the **Main** table group.

  - **Main** – Includes the principal or master tables that contain data for central business objects. These tables typically hold static, base information.

  - **Miscellaneous** – Includes tables that have not been otherwise categorized. This table group is the default group for new tables.

  - **Parameter** – Includes tables that contain parameters or setup information for tables in the **Main** table group.

  - **Reference** – Includes tables that contain reference data.

  - **Transaction**, **Transaction header**, and **Transaction line** – Include tables that contain transaction data. The tables in the **Transaction header** table group categorize the tables in the **Transaction line** table group. There is a one-to-many relationship between a **Transaction header** table and a **Transaction line** table.

  - **Worksheet**, **Worksheet header**, and **Worksheet line** – Include tables that contain information that is validated and made into transactions. Unlike the data that is contained in tables in the **Transaction** table groups, data in the **Worksheet** table groups is temporary. After data from these tables has been made into transactions, and moved into transaction tables, the **Worksheet** tables become obsolete and can be deleted without affecting system stability.

For a list of all the tables that can be accessed from the data dictionary, see [Table and table group reference](table-and-table-group-reference.md).

## See also

[Component architecture](component-architecture.md)

[System architecture](system-architecture.md)

[Configure SQL Server and storage settings](configure-sql-server-and-storage-settings.md)

  


