---
title: Run replenishment manually
TOCTitle: Run replenishment manually
ms:assetid: 6de78380-33b4-4353-87e3-4d47f0245abf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn715964(v=AX.60)
ms:contentKeyID: 62200087
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Run replenishment manually 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to run replenishment for load demand replenishment, and how to run replenishment that is based on minimum and maximum stocking limits. You can schedule replenishment, or you can run it manually by using a batch job. For example, scheduling replenishment is useful if replenishment is based on minimum and maximum stocking limits and you want to refill your picking locations at the end of the workday. For load demand replenishment, this is useful if you cannot fulfill a load due to lack of inventory in a location.

## Run or schedule replenishment for a load demand

To set up and schedule a batch job for replenishment based on load demand, or to manually run replenishment, follow these steps:

1.  Click **Warehouse management** \> **Periodic** \> **Load demand replenishment**.

2.  In the **Replenish template** field, select the replenishment template that you want to use. Only templates that are created for load demand are available.

3.  Do one of the following:
    
      - To run load replenishment and create replenishment work, click **OK**.
    
      - To schedule replenishment, click the **Batch** tab, and set up a batch job.

## Run or schedule replenishment that is based on minimum and maximum stock limits

To set up a schedule for replenishment that is based on minimum and maximum values, or to manually run replenishment, follow these steps:

1.  Click **Warehouse management** \> **Periodic** \> **Replenishments**.

2.  Do one of the following:
    
      - To run replenishment and create replenishment work, click **OK**.
    
      - To schedule replenishment, click the **Batch** tab, and set up a batch job.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


