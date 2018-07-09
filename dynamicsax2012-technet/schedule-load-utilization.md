---
title: Schedule load utilization
TOCTitle: Schedule load utilization
ms:assetid: e912969d-548a-46e9-b735-999e21d9ca49
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ728718(v=AX.60)
ms:contentKeyID: 49556623
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Schedule load utilization [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

You can schedule load utilization for selected location types, and also project the current and future load utilization. You can project the load for one or more sites, for the load units of warehouse or zone, or for a combination of zone and warehouse.

## Schedule and view the load for a warehouse or site

To schedule the load for sites, warehouses, or zones, you create a space utilization setup and associate it with a master plan.

In the space utilization setup, you specify how to project space utilization by using location types, such as **Bulk location** and **Picking location**. You also specify a storage load mode, such as **Zone**.

The projection of future space utilization is based on information that is calculated on the associated master plan. Master plans forecast the resource planning for incoming and outgoing orders for production and operations. The projection of available space is based on the relation between the space utilization setup and the selected master plan.

By using the unit load mode that you selected in the space utilization setup, you specify whether the load should be projected for each warehouse or zone, or if the projections should include information about both warehouse and zone. You also specify if blocked locations should be excluded from the calculation of the load utilization.

The space utilization can be projected by using the **Warehouse load utilization** report. When you generate the report, you can specify whether the load utilization should be projected for each site or across sites or for the selected load unit, such as zone or warehouse.


> [!NOTE]
> <P>If you use Role Centers, you can also view space utilization projections from your Role Center.</P>



## Create a space utilization setup for a warehouse

1.  Click **Inventory management** \> **Setup** \> **Warehouse reports** \> **Space utilization**.

2.  Click **New** to create a space utilization setup. Specify an ID and a name for the setup.

3.  In the **Storage load mode** field, select whether the overview of space utilization should be by warehouse, zone, or warehouse and zone.

4.  Select the **Exclude blocked locations** check box if blocked inventory locations should not be included in the calculation of available space.
    

    > [!TIP]
    > <P>You can block an inventory location for input and output by specifying a blocking cause for the location on the <STRONG>Other</STRONG> tab in the <STRONG>Inventory locations</STRONG> form.</P>



5.  On the **Location type** FastTab, select the location types to include in the space utilization calculation.
    

    > [!NOTE]
    > <P>You must select at least one location type for the projection.</P>



## Associate a space utilization setup with a master plan

1.  Click **Inventory management** \> **Periodic** \> **Schedule load utilization**.

2.  In the **Master plan** field, select a master plan.

3.  In the **Number of days** field, specify the number of days to include in the projection of current and future workloads.

4.  In the **Space utilization** field, select the space utilization setup to use for the projection of current and future workloads.


> [!NOTE]
> <P>You can change between master plans to project the space utilization under varying conditions, as specified in the master plan. For simulation purposes, you can select a different master plan for a space utilization setup. Data is available for all existing master plans.</P>



## Specify the load utilization projection and view information

1.  Click **Inventory management** \> **Reports** \> **Analysis** \> **Warehouse load utilization**.

2.  In the **Show by** field, select **Site** or **Load unit** to identify the level of space utilization projection.
    
      - Select **Site** to project the space utilization for each site. This projection is useful if, for example, you want to view all the warehouses for a site so that you can balance the space utilization between the warehouses.
    
      - Select **Load unit** to project the space utilization for zones or warehouses. The available space is then projected according to the selected option in the **Storage load mode** field in the **Space utilization** form.

3.  In the **Site** field, select one or more sites to include in the projection. This option is available only if you selected **Site** in the **Show by** field.

4.  In the **Load unit** field, select the load unit. This option is available only if you selected **Load unit** in the **Show by** field.

5.  In the **Load type** field, specify **Volume**, **Pallet**, or **Weight** to indicate the warehouse operating unit to project space for.
    

    > [!NOTE]
    > <P>Pallets are available only if the Warehouse Management System (WMS) is enabled. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa548653(v=ax.60)">About license codes and configuration keys</A>.</P>



6.  In the **Space utilization setup** field, select the space utilization setup that the projection will be based on.

## See also

[Space utilization (form)](https://technet.microsoft.com/en-us/library/jj677438\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

