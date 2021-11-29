---
title: Set up accessorial assignments
TOCTitle: Set up accessorial assignments
ms:assetid: 6e62a681-9184-4b5e-bcf0-0c575b33182e
ms:mtpsurl: https://technet.microsoft.com/library/Dn553167(v=AX.60)
ms:contentKeyID: 62200088
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSAccessorialAssignment
- accessorial
- accessorial assignment
- accessorial assignments
- accessorials
audience: Application User
ms.search.region: Global
---

# Set up accessorial assignments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



You can associate a shipping carrier with one or more accessorial assignments for surcharges, such as fuel surcharges. When you rate a shipment, you can calculate accessorial charges and assign those charges to freight transportation services.

## Set up an accessorial assignment

You can set up an accessorial assignment with an optional detail level. For example, you can set filtering options that limit the accessorial assignment to apply for a specific warehouse during a specific period.

To set up an accessorial assignment, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Accessorial assignments**.

2.  On the **Details** FastTab, in the **Name** field, enter a descriptive name for the accessorial assignment.

3.  In the **Carrier accessorial ID** field, select an ID to associate information such as shipping carrier, carrier service, and billing group. For more information, see “Set up a carrier accessorial” in [Set up accessorial charges for a shipping carrier](set-up-accessorial-charges-for-a-shipping-carrier.md).

4.  On the **Criteria** FastTab, select the **Always apply** check box if you want to always calculate fuel surcharges for the selected accessorial fee type with the current set of filter criteria.

5.  On the **Calculation** FastTab, in the **Accessorial fee type** field, select the type of accessorial fee to use to rate freight. The fields on the **Calculation** FastTab change depending on the selection in this field.
    
    The available options for the accessorial fee type are described in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Flat</strong></p></td>
    <td><p>The flat rate without any additional calculations.</p>
    <p>If you select this field, the following field becomes available:</p>
    <ul>
    <li><p><strong>Accessorial fee</strong> – Optional: Enter an assessorial fee to apply when the freight is rated.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Per unit</strong></p></td>
    <td><p>The accessorial charge is calculated per unit of measure for the fuel charge.</p>
    <p>If you select this field, the following fields become available:</p>
    <ul>
    <li><p><strong>Accessorial unit</strong> - Select a rating engine method.</p></li>
    <li><p><strong>Accessorial unit divisor</strong> – Optional: Select a divisor.</p></li>
    <li><p><strong>Maximum charge</strong> and <strong>Minimum charge</strong> - Optional: Enter the maximum and minimum accessorial charges.</p></li>
    <li><p><strong>Currency</strong> - Optional: Change the currency that is derived from the shipping carrier.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Percentage</strong></p></td>
    <td><p>The accessorial fee is a percentage of the base shipping rate.</p>
    <p>Some of the fields that become available when you select this option correspond to the fields listed for <strong>Per unit</strong>.</p>
    <p>In addition to the fields listed for <strong>Per unit</strong>, the following field becomes available:</p>
    <ul>
    <li><p><strong>Percentage</strong> - Enter the percentage to use for calculating accessorial charges.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Fuel surcharge</strong></p></td>
    <td><p>The surcharge rate or percentage based on the carrier’s fuel index.</p>
    <p>Some of the fields that become available when you select this option correspond to the fields listed for <strong>Per unit</strong>.</p>
    <p>In addition to the fields listed for <strong>Per unit</strong>, the following fields become available:</p>
    <ul>
    <li><p><strong>Region</strong> - Optional: Change the region that is derived from the shipping carrier. This is the region where the fuel index is applied.</p></li>
    <li><p><strong>Offset</strong> - Optional: Enter the number of offset days for which the fuel index will apply.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


6.  On the **Calculation** FastTab, select the **Allow a discount** check box to use a shipper rate or a customer rate when accessorial charges are calculated.

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
<td><p><strong>Configuration key</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>


## See also

[Set up carrier fuel indexes](set-up-carrier-fuel-indexes.md)

  


