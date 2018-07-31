---
title: Set up carrier fuel indexes
TOCTitle: Set up carrier fuel indexes
ms:assetid: 274db4e5-1af4-420e-a240-418d493e87e2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553152(v=AX.60)
ms:contentKeyID: 62200045
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSCarrierFuelIndexTable
- carrier fuel index
- carrier fuel indexes
- fuel indexes
- fuel index
audience: Application User
ms.search.region: Global
---

# Set up carrier fuel indexes 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



Fuel indexes are set by the Department of Energy (DOE) for the various regions of the United States. You can set up fuel indexes for different fuel prices so that you can specify a time frame in which the carrier’s fuel charge is based on the specified price.

The carrier fuel index can be associated with one or more fuel indexes.

## Set up fuel index regions

You must set up a fuel index region before you can create a fuel index. The fuel index region determines where freight will be delivered. The region is associated with the shipping carrier through the carrier’s accessorial assignment. For more information about accessorial assignments, see [Set up accessorial assignments](set-up-accessorial-assignments.md).

To set up fuel index regions, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Fuel index regions**.

2.  Click **New** to create a fuel index region.

3.  Enter a unique identification and a name for the fuel index region.

## Create a fuel index

Fuel indexes are associated with a fuel index region. To reflect the change in fuel prices over time, you can associate a region with multiple fuel indexes. Typically, the price information for a fuel index can be downloaded from the Internet.

To create a fuel index, follow these steps:

1.  Click **Transportation management** \> **Periodic** \> **Fuel indexes**.

2.  Click **New**.

3.  In the **Region** field, select a region.

4.  Enter the fuel price per gallon.

5.  In the **Effective date and time for fuel price** field, select the date and enter the time at which the fuel index will go into effect.

## Create a carrier fuel index

The carrier fuel index is part of the carrier’s rating profile. You must set up fuel indexes for carriers that will deliver freight in a specific region. In the carrier fuel index, you specify the per-gallon fuel charge limits for the carrier.

To create a carrier fuel index, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Shipping carrier**.

2.  Select a carrier and then click **Carrier fuel index**.

3.  Click **New**. In the **Carrier fuel index** and the **Description** fields, enter a name and a description for the fuel index.

4.  On the **Details** FastTab, click **New**.

5.  Create a transaction time frame, and complete the following fields.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>PPG From</strong> and <strong>PPG To</strong></p></td>
    <td><p>The price range for the price per gallon. A fuel price in this range is added to the freight charges.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Percentage</strong></p></td>
    <td><p>The percentage of the freight surcharge that is added to the rate. This is a percentage of the accessorial unit that is specified in the carrier’s accessorial assignment.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Rate</strong></p></td>
    <td><p>A flat rate to cover the freight surcharge. This rate is added to the rate that is calculated for the carrier.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Currency</strong></p></td>
    <td><p>The currency of the index.</p></td>
    </tr>
    </tbody>
    </table>


## Associate a shipping carrier with a fuel index region

To calculate fuel surcharges for a shipping carrier, you must specify a fuel index region with the carrier’s accessorial assignment.

To associate a shipping carrier with a fuel index region, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Accessorial assignments**.

2.  Select an accessorial assignment for a shipping carrier.

3.  On the **Calculation** FastTab, in the **Accessorial fee type** field, select **Fuel surcharge**.

4.  In the **Region** field, select the fuel index region.

## Related tasks

[Set up accessorial assignments](set-up-accessorial-assignments.md)

  


