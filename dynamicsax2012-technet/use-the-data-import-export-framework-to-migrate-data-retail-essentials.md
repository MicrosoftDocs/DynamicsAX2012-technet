---
title: Use the Data import/export framework to migrate data (Retail essentials)
TOCTitle: Use the Data import/export framework to migrate data (Retail essentials)
ms:assetid: f5d95348-6740-4578-90e0-98954e9848b7
ms:mtpsurl: https://technet.microsoft.com/library/Dn736977(v=AX.60)
ms:contentKeyID: 62200454
author: Khairunj
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Use the Data import/export framework to migrate data (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to migrate data into Retail essentials. This topic covers the following procedures:

  - Planning the data import

  - Determining target entities

  - Adding target entities

  - Modifying a target mapping


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Planning to import data

If you are moving from another enterprise resource planning (ERP) system to Retail essentials, you might want to import master data and reference data. However, this step is not required.


> [!NOTE]
> <P>Before you import data, close all open transactions that can be closed. For reporting and compliance purposes, maintain the database that contained your previous transactional data.</P>



Data import is a complex process that usually requires many iterations. The general steps in the import process are as follows:

1.  Identify the data in your existing system that must be imported.

2.  Consider cleaning up the data in your existing system. For example, determine whether old records can be deleted or archived, whether the current database contains duplicate records, and whether you want to change numbering schemes.

3.  Become familiar with the relevant data structures in Retail essentials that the data from your existing system must be moved to.
    

    > [!NOTE]
    > <P>Data from one table in another system might have to be moved into multiple tables in Retail essentials.</P>



4.  Determine the appropriate tools and techniques to use for the data that you must import.

5.  Prepare a test Retail essentials environment.

6.  Create a backup of your existing system and your Retail essentials environment before you import any data.

7.  Perform a trial import of all types of data that are required.
    

    > [!NOTE]
    > <P>Expect to encounter errors the first time that you perform an import. Review the errors that you encounter, make any fixes that are required, and perform the import again.</P>



## Determine which Retail essentials entities to use as targets

Each entity must be associated with an entity class, a staging table, and a target entity. For out-of-box entities, these values are pre-populated.

  - The staging table is the table to which the data is written before it is transformed.

  - The entity class is where X++ transformation logic is stored. You can create a copy of an entity class and modify the transformation logic.

  - The target table is the table that fully modified data is written to.

The following special target entity types are also included:

  - A table entity lets you migrate data directly from a source to a target Retail essentials table. You do not have to go through a staging table or apply any business logic.
    
    Unlike other entities, the table entity must be a one-to-one mapping from source to target. Data cannot be pushed from one source table to multiple target tables.

  - A composite entity groups together multiple related entities. An example of a composite entity is a combination of a Sales Order entity and Sales Line entities. Composite entities are supported only for file data sources.

For details about each target entity, see the information in the **Target entities** form.

You must determine which entities you plan to migrate to Retail essentials.


> [!IMPORTANT]
> <P>The mapping from the staging schema to the target schema is automatically generated. Unless you have customized your Retail essentials system, you should not have to modify the staging-to-target mapping.</P>



## Add a target entity

You can add table entities, composite entities, and custom entities to the Data Import/Export Framework.

1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Data import export framework** \> **Target entities**.

2.  Click **New**, and then, in the **Entity type** field, select the entity type to add.
    
      - If you select the **Table** entity type, enter a name, and then select a staging table and a target entity.
    
      - If you select the **Composite entity** entity type, enter a name, and then click **Child entities** to specify the entities that comprise the composite entity.
        

        > [!NOTE]
        > <P>At least one child entity in each composite entity must include a <STRONG>RowID</STRONG> field. By default, the Data Import/Export Framework is released with the following entities that contain a <STRONG>RowID</STRONG> field and can be used in composite entities: DMFSalesTableEntity, DMFSalesLineEntity, DMFPurchTableEntity, DMFPurchLineEntity, DMFBOMEntity, and DMFBOMVersionEntity. To create a composite entity for a group of entities that is not supported by default, you must create a custom target entity by using the wizard.</P>



3.  For a custom entity type, enter a name, and then specify the staging table, entity class, and target entity.

## Modify a target mapping

You can change the sequence in which fields are processed. You can also enable a field to call the **validateField** method or the **modifiedField** method to check business logic when the field is processed.


> [!IMPORTANT]
> <P>Even if you set the <STRONG>Call validateField method</STRONG> or <STRONG>Call modifiedField method</STRONG> value for a field, the method might not be run. These values only enable the methods to be run. However, the settings for the processing group determine whether a method is actually run.</P>



1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Data import export framework** \> **Target entities**.

2.  Select the target entity to modify, and then click **Modify target mapping**. The **Map staging to target** form opens.
    
    The default **Mapping visualization** view displays the staging fields, functions (entity classes that contain transformations), and target fields that are associated with the target entity.

3.  Click **Mapping details**.

4.  To modify the order in which a field is processed, change the **Sequence** value.

5.  To enable a field to be run together with any business logic in the **validateField** method, select **Call validateField method**.

6.  To enable a field to be run together with any business logic in the **modifiedField** method, select **Call modifiedField method**.

## See also

[Configure and schedule data distribution for retail stores (Retail essentials)](configure-and-schedule-data-distribution-for-retail-stores-retail-essentials.md)

  


