---
title: Configure Master Data Management
TOCTitle: Configure Master Data Management
ms:assetid: aba9a95c-69fc-43bc-8d49-162eca16601e
ms:mtpsurl: https://technet.microsoft.com/library/Dn720447(v=AX.60)
ms:contentKeyID: 62224153
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Configure Master Data Management 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can configure several aspects of Master Data Management (MDM) to suit your business requirements. You can specify which Microsoft Dynamics AX 2012 R3 spokes can update master data during synchronization, and which spokes can only read data. You can set synchronization schedules for each spoke to determine when the entities in that instance are synced with the central store. You can also filter data during the push and pull operations to constrain the records or fields that are sent or received.

## Determine Which Spokes Can Write Data

You can configure your MDM environment as either a multi-master or a single-master environment. In a multi-master configuration, any participating Microsoft Dynamics AX 2012 instance can modify master data records. Conflicts are automatically detected in Microsoft SQL Server Master Data Services (SQL MDS) at the record level. The records that are in conflict are set aside in SQL MDS until you resolve the issue. You resolve issues manually by using the SQL Server Master Data Services Add-in for Microsoft Excel.


> [!NOTE]
> <P>As a best practice in multi-master configurations, you should partition natural keys, such as number sequences for record identifiers, so that they do not collide across instances. For example, you do not want two instances to create two different customer records that have the same ID.</P>



In a single-master configuration, only one AX 2012 instance can write to MDS, and all other instances are read-only. Any change to data in MDM-subscribed entities on the read-only instances is overwritten during synchronization if the data differs from the data in the central store. This approach removes the requirement for conflict management, but also requires security customization and some decisions about business policy. You must customize roles to prevent users in read-only instances from updating records in subscribed entities. You must also determine your business policy about how and when data in subscribed entities is created and updated, and make sure that users across all instances understand how to work with this data.

You must decide whether you want a multi-master or single-master environment before you configure synchronization. The type of environment determines the synchronization operations that you create on each participating AX 2012 instance.

## Configure Synchronization

Synchronization consists of push operations, which send data updates to the SQL MDS hub, and pull operations, which retrieve master data from the hub to an AX 2012 spoke. In a multi-master environment, both push and pull operations are configured for all spokes. In a single master environment, pull operations are configured for all spokes, but only one spoke also has push operations.

You can schedule synchronization operations for each subscribed entity on a spoke by adding the entity to a sync group. A sync group contains one entity or a list of multiple entities in a sync sequence. A sync group is associated with a task, and this task determines the following information about the synchronization operations of the entities in the sync group:

  - The recurrence schedule.

  - The batch status. The status indicates whether the task is run as part of a batch, what batch group the task belongs to, and whether you receive alerts about the status of batch processing.

An entity can be synchronized only if it belongs to a sync group. An entity can belong to only one sync group.

After an entity has been added to a sync group, you can set the synchronization settings for that entity. For example, you can specify whether the entity uses push and pull operations or just pull operations. You can also specify what data sets are used for those operations.

## Create a Sync Group

To create a sync group, follow these steps.

1.  In AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **Manage Synchronization**.

3.  In the **Manage Synchronization** form, click **New** to create a sync group.

4.  In the **Create a New Synchronization Group** form, enter a name and select a company for the sync group. The company uses your current company. When you have finished, click **OK**.
    

    > [!NOTE]
    > <P>If your entities and underlying tables are company-specific, synchronization is also company-specific. For global tables, one sync group synchronizes all the data, except the data in different partitions.</P>



## Add an Entity to a Sync Group

Add entities to a sync group in the order in which their synchronization operations should run. If entities are not related, the order does not make a difference. However, if entities are related, the order does make a difference. For example, if you have an Address entity that depends on a Regions entity, you should synchronize the Regions entity first.

To add an entity to a sync group, follow these steps.

1.  In AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **Manage Synchronization**.

3.  Select the sync group to add an entity to, and then click **Entities**.

4.  In the **Select entities** form, follow one of these steps.
    
      - If this entity is the first entity that you are adding to the sync group, select the entity in the **Entity** field. The **Sequence** value is automatically set to **1**.
    
      - If you have already added entities to the sync group, click **New** to add another row. Then, in the **Entity** field, select the entity. The **Sequence** value increments automatically.

5.  Repeat step 4 to add all the entities that you require to the sync group. Then click **Close**.

## Set Up Synchronization for an Entity

To configure synchronization for an entity, follow these steps.

1.  In AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **Manage Synchronization**.

3.  Select the sync group that contains the entity to synchronize, and then click **Entities**.

4.  Select the entity that you want, and then click **Settings**.

5.  In the **Synchronization settings for the master data management entity** form, set the following values for the entity:
    
      - **Synchronization type** – If you have a multi-master environment, select Push and pull. If you have a single-master environment and this spoke is the single master, select Push and pull. If this spoke is a read-only spoke, select Pull only to pull data and disable push operations.
    
      - **Subscription view** – Select the view that defines the master data to pull from SQL MDS for this entity. The default view is named **DMF\<Entity name\>Entity\_View** and that contains all entity records. For more information about how to filter pulled data, see “Filter the Data That Is Pulled from SQL MDS,” later in this topic.
    
      - **Number of records** – Set the number of records that are handled per thread. Typically, you leave this setting at the default value of **1**. However, you can increase the value to increase throughput when you are processing lots of records. Use this setting together with the **Number of tasks** setting to manage throughput.
    
      - **Number of tasks** – Set the number of records that are handled per thread. Typically, you leave this setting at the default value of **3**, but you can increase the value to increase throughput when you are processing lots of records. Use this setting together with the **Number of records** setting to manage throughput.
    
      - **Query for export** – Select the query that defines the data to push to SQL MDS for this entity. The default query is named **DMF\<Entity name\>TargetEntity** and that contains all entity records. For more information about how to filter pushed data, see “Filter the Data That Is Pushed to SQL MDS,” later in this topic.

6.  When you have finished setting the synchronization values, click **Close**.

## Schedule a Sync Group

To schedule a sync group, follow these steps.

1.  In AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **Manage Synchronization**.

3.  In the **Manage Synchronization** form, select a sync group, and then click **New schedule**.

4.  In the **MDM synchronization** form, click **Recurrence**, and then set the following values:
    
      - The time zone – Your current time zone is used.
    
      - The range of the recurrence – This value includes a start date and time, and an end date. For the end date, you can specify a date, select the number of times that the task runs before it expires, or indicate that the task has no end date and runs indefinitely.
    
      - The recurrence pattern – This value includes the unit of time that is used and the frequency with which the task runs. Recurrence units range from minutes to years to allow for precise scheduling.
    
    For example, you want a task to start Wednesday, May 7, 2014, at 1:00 A.M. Pacific Standard Time, and you want the task to recur every Wednesday a total of 10 times. In this case, you specify the following values:
    
      - In the **Time zone** field, select **(GMT-08:00) Pacific Time (US & Canada)**.
    
      - In the **Starting time** field, enter **01:00:00 am**.
    
      - In the **Starting date** field, enter **5/7/2014**.
    
      - Select **End after**, and then, in the **Count** field, enter 10.
    
      - Select **Weeks**. Clear **Monday**, and select **Wednesday**. Leave the **Fixed weekly interval** value at **1**.
    
    When you have finished creating the schedule, click **OK**.

5.  Typically, you run the task as part of a batch. Select **Batch processing**, and then, in the **Batch group** field, select a group.

6.  Click **Alerts**, and then select the alerts to receive. You can receive alerts when a batch job ends, is canceled, or raises an error. You can also select to receive other types of alerts as pop-ups. When you have finished, click **OK**.

7.  When you have finished configuring the sync group, click **OK**.

## Filter Data

You use filtering to determine what master data is shared between the SQL MDS hub and an AX 2012 spoke. You can set different filter parameters for each subscribed entity on each spoke.

For filtering during push operations, entity data that is sent to the hub is constrained based on a query that you create in MDM. For example, your vendors can be used in all geographic locations only if they meet specific requirements. In this case, you might want to send only vendor records that are approved for use across the company to the master data store.

For filtering during pull operations, entity data that is retrieved from the hub is constrained based on a subscription view that you create in SQL MDS. For example, if you have subsidiaries in multiple geographic locations, you might want the AX 2012 spoke in each location to pull down only products that are sold in that region.

## Filter the Data That Is Pushed to SQL MDS

To filter data during a push operation from an AX 2012 spoke to the SQL MDS hub, follow these steps.

1.  In AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **Manage Synchronization**.

3.  In the **Manage Synchronization** form, select the sync group for the entity, and then click **Entities**.

4.  Select the entity to filter, and then click **Settings**.

5.  Click **Edit** to modify the query for export. A form that has the name of the entity opens. This form displays the tables that are associated with the selected entity.

6.  On the **Range** tab, in the **Table** and **Field** columns, select the table and field to filter on. Then, in the **Criteria** column, enter a filter criterion. To specify more filter criteria, click **Add** to add a new row. The data that is sent to SQL MDS is constrained based on the criteria that you specify. For example, if you filter on the **Name** field of the Customer table, and you select **Contoso LTD** as the filter criterion, only records for that company are selected.

7.  You can specify the sort order in which the query results are displayed. On the **Sorting** tab, click **Add** to add a row. Then, in the **Table** and **Field** columns, select the table and field to sort on. In the **Search direction** column, indicate whether the sort order should be ascending or descending. To specify more sort order criteria, click **Add** to add a row. To move sort order criteria up or down, select a row, and then click **Up** or **Down**. For example, you are sorting by customer name and then by region, but you then decide that you want to sort by region first. In this case, you select the row for region and then click **Up**.

8.  When you have finished specifying query criteria, click **OK**. Close the **Settings** form and the **Entities** form.

## Filter the Data That Is Pulled from SQL MDS

To filter data during a pull operation from the SQL MDS hub to an AX 2012 spoke, follow these steps.

1.  In the SQL MDS web application, click **Integration Management**, and then click **Create Views**.

2.  Click **+** to add a subscription view.

3.  On the **Subscription Views** page, enter the following information:
    
    1.  In the **Subscription view name** field, enter a name for the view.
    
    2.  In the **Model** field, select the model for the entity. Typically, the model name is the same as the entity name.
    
    3.  In the **Version** field, select the highest version that is available.
    
    4.  In the **Entity** field, select the subscribing entity.
    
    5.  In the **Format** field, select Leaf members.
    
    When you have finished entering view data, click **Save** (the floppy disk button on the left side of the page).

4.  In SQL Server Management Studio, in Object Explorer, select the SQL MDS database.

5.  Expand the database and then the **Views** folder. Then select the view that you just created in the SQL MDS web application. If you do not see this view, refresh the **Views** folder.

6.  Right-click the view, and then click **Design**. Use the SQL Server query tools to modify the view until it returns the data set that you want. For more information about how to modify views, see [Modify Views](https://go.microsoft.com/fwlink/?linkid=394376).

7.  Open a new query window, and run the command SELECT \* from \<View Name\>. Review the results to verify that your view returns the data that you expect.

8.  In AX 2012, open **Data import export framework**.

9.  In **Master data management**, click **Manage Synchronization**.

10. In the **Manage Synchronization** form, select the sync group for the entity, and then click **Entities**.

11. Select the entity to associate with the view, and then click **Settings**.

12. In the **Synchronization settings** form, in the **Subscription view for import** field, select the new view, and then click **Close**.

  


