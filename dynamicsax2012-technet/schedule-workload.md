---
title: Schedule workload
TOCTitle: Schedule workload
ms:assetid: 579ee934-c0bf-404a-a8a5-ea3e7c085487
ms:mtpsurl: https://technet.microsoft.com/library/JJ728689(v=AX.60)
ms:contentKeyID: 49556593
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Schedule workload 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

You can schedule workload capacity for warehouses, and also project the current and future workloads for the workers in individual warehouses. You can project the workload for the whole warehouse, or you can project the workload separately for incoming and outgoing workloads.


> [!NOTE]
> <P>To project workload output for selected warehouses, master scheduling data must be available for the selected warehouses. For more information, see <A href="about-master-scheduling-plans.md">About master scheduling plans</A>.</P>



## Schedule and view workloads for a warehouse

To schedule workload capacity for a warehouse, you create a workload setup for one or more warehouses, and then associate the workload setup with a master plan. In the workload capacity setup, you can define limits on pallets, weight, or volume for incoming and outgoing transactions. You can also create more than one setup for each warehouse, and then associate the setup with individual master plans. For example, you might do this to comply with seasonal changes in the workforce.

If the workers for a warehouse work with transactions for both incoming and outgoing workloads, you can configure the warehouse capacity setup to project the workload in a combined view.

On the **Workload capacity** report, you can view current and future workloads, and how the workloads comply with the limits that you defined for incoming and outgoing transactions.


> [!TIP]
> <P>If you use Role Centers to monitor data, you can also view the workload capacity on your Role Center.</P>



To schedule and view workloads for warehouses, you must do the following tasks:

1.  Create a workload capacity setup and define workload capacity limits for one or more warehouses.

2.  Associate the workload capacity setup with a master plan to create workload projections and to specify how long the projections will apply.

## Create a workload capacity setup for a warehouse

1.  Click **Inventory management** \> **Setup** \> **Warehouse reports** \> **Workload capacity**.

2.  Click **New** at the top of the form to create a workload capacity setup.

3.  Click **New** in the FastTabs section of the form, and then enter values on the line to associate a warehouse with the workload capacity setup.

4.  Enter values in the fields for the incoming and outgoing pallet limits, volume limit, or weight limit to set the capacity limits for the warehouse.
    

    > [!NOTE]
    > <P>You can set up limits for pallets, volume, or weight depending on which limitations are relevant for the warehouse workforce. The limits that you specify are included in the workload capacity projection that you can view on the <STRONG>Workload capacity</STRONG> report.</P>
    > <P>To project information about pallets, volume, and weight for items, the standard pallet type, volume of one inventory item, and weight of one inventory item must be specified for all products. The fields that are required are available in the <STRONG>Released product details</STRONG> form on the <STRONG>Manage inventory</STRONG> FastTab, in the following field groups:</P>
    > <UL>
    > <LI>
    > <P><STRONG>Handling</STRONG></P>
    > <LI>
    > <P><STRONG>Physical dimensions</STRONG></P>
    > <LI>
    > <P><STRONG>Weight measurements</STRONG></P></LI></UL>
    > <P>If this information is not specified correctly, you will receive a message when you generate the <STRONG>Workload capacity</STRONG> report. From the report, you can drill down to identify the information that is missing to project the future workload.</P>



5.  Select the **Combined inbound and outbound workload** check box to display the total workload for incoming and outgoing transactions in one view on the **Workload capacity** report.

6.  On the **Transaction types** FastTab, select the incoming and outgoing transaction types that the workload limits will apply to.
    

    > [!NOTE]
    > <P>You must select at least one transaction type for both the incoming and outgoing workloads.</P>



## Associate a workload capacity setup with a master plan

1.  Click **Inventory management** \> **Periodic** \> **Schedule workload**.

2.  In the **Master plan** field, select the master plan to use for workload projections.
    

    > [!TIP]
    > <P>You can change between master plans to project the workload under varying conditions, as specified in the master plan.</P>



3.  In the **Number of days** field, specify the number of days that the workload projection covers.

4.  In the **Workload** field, select the workload setup to associate with the master plan.

## View workload capacity

1.  Click **Inventory management** \> **Reports** \> **Analysis** \> **Workload capacity**.

2.  In the **Number of columns** field, specify the number of columns to display on the report.

3.  In the **Order type** field, select **Planned and confirmed**, **Planned**, or **Confirmed** to indicate the type of orders to project on the report.

4.  In the **Load type** field, select a load type to indicate if the workload capacity should be projected for pallets, volume, or weight.

5.  In the **Workload capacity** field, select a workload capacity setup.

  


