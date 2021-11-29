---
title: About system-generated quality orders
TOCTitle: About system-generated quality orders
ms:assetid: dcb92041-74b3-47f6-aada-19245f5c13d4
ms:mtpsurl: https://technet.microsoft.com/library/Gg243194(v=AX.60)
ms:contentKeyID: 44081053
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- automate quality orders
- automatically generate a quality order
- conditions for generating a quality order
- quality association record
audience: Application User
ms.search.region: Global
---

# About system-generated quality orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a quality association, the system can generate quality orders for various business processes, events, and conditions. The quality association can cover a specific item, a specific group of items, or all items. Quality associations are created in the **Quality associations** form.

## Working with quality associations

The business process that uses a quality association can be related to purchase orders, sales orders, or production orders.


> [!TIP]
> <P>In the <STRONG>Quality associations</STRONG> form, the business process is referred to as the reference type.</P>



Each quality association record defines the set of tests, the acceptable quality level (AQL), and the sampling plan that applies to the quality orders that are generated. A quality association record must be defined for each variation in a business process. For example, you can set up a quality association that generates a quality order either before or after a packing slip is posted.


> [!NOTE]
> <P>Inventory quantities that are specified in a quality order are automatically blocked from being issued.</P>



For a given business process, the quality association record identifies the event and the conditions for which a quality order is generated. The conditions can be specific either to a site or to a legal entity. A quality order that involves destructive tests can be generated only when on-hand inventory exists for the event.

The following examples illustrate how a quality association record is defined for the variations in each business process. For each example, the following diagram summarizes the events and conditions that are defined by a quality association record.

![Events and conditions of a quality association](images/Gg243194.Quality_associations_and_guidelines_for_automatic_generation_of_quality_order(AX.60).gif "Events and conditions of a quality association")

The following table provides more information about how quality orders can be generated for specific types of processes.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of process</p></th>
<th><p>When quality orders can be automatically generated</p></th>
<th><p>When quality orders can be generated if destructive testing is required</p></th>
<th><p>Condition information</p></th>
<th><p>Manual generation information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Purchase order</p></td>
<td><p>Before or after a receipts list or product receipt for the material that is received is posted</p></td>
<td><p>After the product receipt for the material that is received is posted, because the material must be available for destructive testing</p></td>
<td><p>The requirement for a quality order can reflect a particular site, item, or vendor, or a combination of these conditions.</p></td>
<td><p>A manually generated quality order that refers to a purchase order can use information in a quality association record, such as the test sampling plan.</p></td>
</tr>
<tr class="even">
<td><p>Quarantine order</p></td>
<td><p>Before or after the quarantine order is reported as finished or ended</p></td>
<td><p>Quality orders that require destructive tests cannot be generated. It is assumed that the quarantine order functionality handles the disposition of the material that is destroyed.</p></td>
<td><p>The requirement for a quality order can reflect a particular site, item, or vendor, or a combination of these conditions.</p></td>
<td><p>A manually generated quality order that refers to a quarantine order can use information in a quality association record, such as the test sampling plan.</p></td>
</tr>
<tr class="odd">
<td><p>Sales order</p></td>
<td><p>Before or after a picking list or packing slip for the material that is being shipped is posted</p></td>
<td><p>At any step</p></td>
<td><p>The requirement for a quality order can reflect a particular site, item, or customer, or a combination of these conditions.</p></td>
<td><p>A manually generated quality order that refers to a sales order can use information in a quality association record, such as the test sampling plan.</p></td>
</tr>
<tr class="even">
<td><p>Production order</p></td>
<td><p>Before or after the finished quantity for the production order is reported</p></td>
<td><p>After the finished quantity for the production order is reported</p></td>
<td><p>The requirement for a quality order can reflect a particular site or item, or a combination of these conditions.</p></td>
<td><p>A manually generated quality order that refers to a production order can use information in a quality association record, such as the test sampling plan.</p></td>
</tr>
<tr class="odd">
<td><p>Production order that has a route operation</p></td>
<td><p>Before or after the report is finished for an operation</p></td>
<td><p>After the reporting production is finished for the last operation</p></td>
<td><p>The requirement for a quality order can reflect a particular, site, item, or operations resource, or a combination of these conditions.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inventory</p></td>
<td><p>A quality order cannot be automatically generated for a transaction in an inventory journal or for transfer order transactions</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>A quality order must be created manually for an item's inventory quantity.</p></td>
</tr>
</tbody>
</table>


## See also

[Quality orders (form)](https://technet.microsoft.com/library/hh209521\(v=ax.60\))

[About inventory blocking](about-inventory-blocking.md)

  


