---
title: About service object relations
TOCTitle: About service object relations
ms:assetid: 19461121-2cff-4ef2-b1ca-bed6799b7850
ms:mtpsurl: https://technet.microsoft.com/library/Aa569915(v=AX.60)
ms:contentKeyID: 37832492
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About service object relations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create service object relations between a service object and a service agreement or service order. When you create a relation, you attach the service object to the service agreement or service order.

After the relation is created, you can attach the service object to any lines on the service agreement or service order.

## Template BOMs

You can also specify a template BOM for the object relation. The template BOM is a bill of materials for the object on which you perform service. If you replace a component part of the service object during a service visit, you can register this change in the service BOM by using the **Service objects** form.

## Example

You create a service agreement for servicing two elevators at a customer site. The service agreement has the identifier ID SAL-001.

The elevators are set up in the **Service objects** form as objects, EL-S/1000 and EL-L/1000.

You attach the service objects, EL-S/1000 and EL-L/1000, to the service agreement.

You want to register changes in the BOM for the service object as you replace component parts of the object, so you attach a service BOM to the service object relation, as described in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service object</p></th>
<th><p>Relation – Service agreement</p></th>
<th><p>Service BOM</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>EL-S/1000</p></td>
<td><p>ID SAL-001</p></td>
<td><p>BOM-EL-S/1000</p></td>
</tr>
<tr class="even">
<td><p>EL-L/1000</p></td>
<td><p>ID SAL-001</p></td>
<td><p>BOM-EL-L/1000</p></td>
</tr>
</tbody>
</table>


Because there are service object relations for the agreement, you can now create service agreement lines with these objects, as shown in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction type</p></th>
<th><p>Category</p></th>
<th><p>Service object</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Hour</p></td>
<td><p>Inspection</p></td>
<td><p>EL-S/1000</p></td>
</tr>
<tr class="even">
<td><p>Hour</p></td>
<td><p>Gear box cleaning</p></td>
<td><p>EL-S/1000</p></td>
</tr>
<tr class="odd">
<td><p>Item</p></td>
<td><p>Cleaning materials</p></td>
<td><p>EL-S/1000</p></td>
</tr>
<tr class="even">
<td><p>Hour</p></td>
<td><p>Inspection</p></td>
<td><p>EL-L/1000</p></td>
</tr>
<tr class="odd">
<td><p>Hour</p></td>
<td><p>Gearbox cleaning</p></td>
<td><p>EL-L/1000</p></td>
</tr>
<tr class="even">
<td><p>Item</p></td>
<td><p>Cleaning materials</p></td>
<td><p>EL-L/1000</p></td>
</tr>
</tbody>
</table>


On a service visit, you have to replace the gearbox for elevator EL-S/1000. To replace a component part of the object, you can access the BOM Designer by using the service object relation that you set up for the current service agreement.

## Access the BOM Designer by using a service object relation

1.  Click **Service management** \> **Common** \> **Service agreements** \> **Service agreements**.

2.  Double-click a service agreement, or click **Service agreement** to create a service agreement.

3.  Click the **Setup** tab.

4.  Click **Service objects** to attach a template BOM to the service agreement.

5.  In the **Service objects** form, click **Designer** to open the **Designer** form to modify the template BOM.

## Automatically created service orders

If you automatically create service orders for a service agreement, the service object relations in the agreement are also created in the service orders.

## See also

[Modify a Service BOM](modify-a-service-bom.md)

[Create service orders automatically](create-service-orders-automatically.md)

  


