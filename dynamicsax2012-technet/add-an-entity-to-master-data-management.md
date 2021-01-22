---
title: Add an Entity to Master Data Management
TOCTitle: Add an Entity to Master Data Management
ms:assetid: 689d14ed-f580-4d41-ac9c-08a880403c40
ms:mtpsurl: https://technet.microsoft.com/library/Dn720445(v=AX.60)
ms:contentKeyID: 62224152
author: Khairunj
ms.author: daxcpft
ms.date: 04/25/2014
mtps_version: v=AX.60
---

# Add an Entity to Master Data Management 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Out of the box, Microsoft Dynamics AX Master Data Management (MDM) supports synchronization of the Customers, Vendors, Employees, Global Address Book, and Product entities. To synchronize any other data, you can use an existing entity or create a custom Data Import/Export Framework entity and then add settings that make the Data Import/Export Framework entity available to MDM. MDM does not support compound Data Import/Export Framework entities.

## Add an Existing Entity to MDM

To add an existing entity to MDM, follow these steps.

1.  In Microsoft Dynamics AX, go to **Data import export framework** \> **Setup** \> **Target entities**. Locate the entity to enable for MDM, and record the entity name, staging table, entity class, and target table.

2.  Open a development workspace, and add a change tracking query for the entity:
    
    1.  Right-click the **Queries** folder, and then click **New query**.
    
    2.  Right-click the new query, and then click **Rename**.
    
    3.  Rename the query Mdm\<staging\_table\_name\>CTQuery.

3.  Add the tables that the entity is based on as the data source for the change tracking query. You must add all the tables that the entity is based on as data sources for the query and create relationships between them. This allows MDM to monitor all of the related tables for changes. For instructions, see [How to: Create Queries by using the AOT](https://technet.microsoft.com/library/bb314753\(v=ax.60\)).
    

    > [!NOTE]
    > <P>DMFCustomerEntityCTQuery is a good example of query based on multiple related tables.</P>



4.  Expand the **DataDictionary** folder, expand **Tables**, expand **DMFEntity**, and then expand the **Methods** folder. Double-click the **DefaultEntityEx** method to open it.

5.  In the switch statement in the **DefaultEntityEx** method, add a case statement that is named case DMFEntityType::\<entity name\>:. Add the following code to make the entity visible in MDM forms. Substitute the entity information that you recorded in step 1.
    
        case DMFEntityType:: <entity name>::
        this.TargetEntity = queryStr(<entity target table name>);
        this.EntityClass  = classStr(<entity class name>);
        this.EntityTable  = tableStr(<entity staging table name>);
        this.Mdm = NoYes::Yes;
        isfound = true;
        break;
    
    The following example shows the code for the Barcode setup entity.
    
        case DMFEntityType::BarcodeSetup:
        this.TargetEntity = queryStr(DMFBarcodeSetupTargetEntity);
        this.EntityClass  = classStr(DMFBarcodeSetupEntityClass);
        this.EntityTable  = tableStr(DMFBarcodeSetupEntity);
        this.Mdm = NoYes::Yes;
        isfound = true;
        break;

6.  Click **Compile**, and then click **Save**.

7.  Right-click the **DMFEntity** table, and then click **Open**. Locate the row for the entity you are enabling for MDM, and select the **Mdm** checkbox for that entity. When you are finished, click **Close**.

8.  Expand the **DataDictionary** folder, expand the entity staging table, and then expand the **Fields** folder. Identify the natural key field for this table. Right-click the field, and then click **Properties**. The development workspace displays the properties of the field. Record the values for the **Type** and **StringSize** properties.

9.  In the staging table that MDM will use, create a key field: right-click **Fields**, click **New**, and then click the data type that matches the value of the **Type** property for the natural key.

10. Right-click the new field, and then click **Properties**. Rename the field AxMdmCode, and modify other properties as required, so that the field matches the natural key field. For example, modify the **StringSize** property.

11. In the staging table, right-click the **Methods** folder, click **Override method**, and then click **insert**. Modify the **insert** method by adding the following line before the super(); line.
    
    this.AxMdmCode = this.\<staging table natural key field\>;
    
    MDM uses this field for change tracking. If a conflict occurs, MDM replaces the value of this field in the secondary record with a GUID, but the natural key remains the same. The primary record still has the natural key value in this field. Therefore, you can see that two records are the same, because they have the same natural key. However, you can also see that the fields are in conflict, because the **AxMdmcode** values do not match. The following example shows a natural key field that is named **AccountKey**.
    
        public void Insert()
        {
        this.AxMdmCode = this.AccountKey;
        super();
        }

12. Click **Compile**, and then click **Save**.

13. In Microsoft Dynamics AX, go to **Data import export framework** \> **Setup**, and then click **Target entities**.

14. In the **Target entities** form, click **New**. In the row that is added, in the first **Entity** field, select the entity that you have enabled for MDM. In the second **Entity** field, enter a unique name for the entity.

15. Select the entity row, and then click **Modify target mapping**. In the **Map staging to target** form, verify that staging-to-target mapping is correct. Make any corrections that are required, and then click **Save**. When you have finished, click **Close**.

16. Click **Validate** to validate the new entity.

17. When validation is completed, click **Close**.

18. In **Master data management**, click **Publish entities to SQL Master Data Services**. In the **Publish entities to SQL Master Data Services** form, select the entity that you enabled, and then click **Create schema** to publish the entity. When the schema has been created, click **Close**.

## Add a Custom Entity to MDM

To create a custom entity and add it to MDM, follow these steps.

1.  Create a custom Data Import/Export Framework entity for the table that contains the data to manage. For instructions, see the section of [Create a custom target entity for the Data Import/Export Framework](https://go.microsoft.com/fwlink/?linkid=394382) that describe how to add an entity by using the data import/export wizard. When the wizard is completed, you are prompted one or more times to add a field to the current table, based on the EDT relation. Click **Yes** for each prompt.

2.  In the **Project** form that opens for the new entity, add a change tracking query for the entity:
    
    1.  Right-click the **Queries** folder, click **New**, and then click **Query**.
    
    2.  Right-click the new query, and then click **Rename**.
    
    3.  Rename the query Mdm\<staging\_table\_name\>CTQuery.

3.  Open a development workspace, and locate the change tracking query in the **Queries** node. Add the tables that the entity is based on as the data source for the change tracking query. You must add all the tables that the entity is based on as data sources for the query and create relationships between them. This allows MDM to monitor all of the related tables for changes. For instructions, see [How to: Create Queries by using the AOT](https://technet.microsoft.com/library/bb314753\(v=ax.60\)).
    

    > [!NOTE]
    > <P>DMFCustomerEntityCTQuery is a good example of query based on multiple related tables.</P>



4.  In the **Project** form for the new entity, expand the **DataDictionary** folder, expand **DMFEntity**, and then expand the **Methods** folder. Double-click the **DefaultEntityEx** method to open it in a development workspace.

5.  In the switch statement in the **DefaultEntityEx** method, locate the case statement that corresponds to the entity. This case statement is named case DMFEntityType::\<entity table name\>:. After the this.EntityTable = tableStr(\<entity name\>); line, add the line this.Mdm = NoYes::Yes;. This line makes the new entity visible in MDM forms. The code should resemble the following example.
    
        case DMFEntityType::Test:
        this.TargetEntity = queryStr(DMFTestTargetEntity);
        this.EntityClass  = classStr(DMFTestEntityClass);
        this.EntityTable  = tableStr(DMFTestEntity);
        this.Mdm = NoYes::Yes;
        isfound = true;
        break;

6.  Click **Compile**, and then click **Save**.

7.  In the **Project** form for the new entity, expand the **DataDictionary** folder, expand the staging table that has the same name as the entity, and then expand the **Fields** folder. Identify the natural key field for this table. Right-click the field, and then click **Properties**. The development workspace that opens displays the properties of the field. Record the values for the **Type** and **StringSize** properties.

8.  In the **Project** form for the new entity, create a key field in the staging table that MDM will use. Expand the **DataDictionary** folder, expand the staging table, right-click **Fields**, click **New**, and then click the data type that matches the value of the **Type** property for the natural key.

9.  Right-click the new field, and then click **Properties**. The development workspace that displays the properties of the field. Rename the field AxMdmCode, and modify other properties as required, so that the field matches the natural key field. For example, modify the **StringSize** property.

10. In the **Project** form, expand the **DataDictionary** folder, and then expand the staging table. Right-click the **Methods** folder, click **Override method**, and then click **insert**. Modify the **insert** method by adding the following line before the super(); line.
    
    this.AxMdmCode = this.\<staging table natural key field\>;
    
    MDM uses this field for change tracking. If a conflict occurs, MDM replaces the value of this field in the secondary record with a GUID, but the natural key remains the same. The primary record still has the natural key value in this field. Therefore, you can see that two records are the same, because they have the same natural key. However, you can also see that the fields are in conflict, because the **AxMdmcode** values do not match. The following example shows a natural key field that is named **AccountKey**.
    
        public void Insert()
        {
        this.AxMdmCode = this.AccountKey;
        super();
        }

11. Click **Compile**, and then click **Save**.

12. In Microsoft Dynamics AX, open **Data import export framework**.

13. In **Setup**, click **Target entities**.

14. In the **Target entities** form, click **New**. In the row that is added, in the first **Entity** field, select the entity that you created. In the second **Entity** field, enter a unique name for the entity.

15. Select the entity row, and then click **Modify target mapping**. In the **Map staging to target** form, verify that staging-to-target mapping is correct. Make any corrections that are required, and then click **Save**. When you have finished, click **Close**.

16. Click **Validate** to validate the new entity.

17. When validation is completed, click **Close**.

18. In **Master data management**, click **Publish entities to SQL Master Data Services**. In the **Publish entities to SQL Master Data Services** form, select the entity that you created, and then click **Create schema** to publish the entity. When the schema has been created, click **Close**.

  


