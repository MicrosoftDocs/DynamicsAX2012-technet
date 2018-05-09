---
title: ShipmentPublishingActionStatus Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipmentPublishingActionStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingActionStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentpublishingactionstatus(v=AX.60)
ms:contentKeyID: 62210008
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingActionStatus.Failed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingActionStatus.InProgress
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingActionStatus.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingActionStatus.Done
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingActionStatus
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentPublishingActionStatus Enumeration

Possible publishing status for a shipment.

This enumeration has a [FlagsAttribute](https://technet.microsoft.com/en-us/library/dk06fkbc\(v=ax.60\)) attribute that allows a bitwise combination of its member values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<FlagsAttribute> _
Public Enumeration ShipmentPublishingActionStatus
'Usage
Dim instance As ShipmentPublishingActionStatus
```

``` csharp
[FlagsAttribute]
public enum ShipmentPublishingActionStatus
```

``` c++
[FlagsAttribute]
public enum class ShipmentPublishingActionStatus
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>No publishing action status.</td>
</tr>
<tr class="even">
<td></td>
<td>InProgress</td>
<td>A status indicating that publishing is currently in progress.</td>
</tr>
<tr class="odd">
<td></td>
<td>Done</td>
<td>A status indicating that publishing has completed successfully.</td>
</tr>
<tr class="even">
<td></td>
<td>Failed</td>
<td>A status indicating that publishing has failed.</td>
</tr>
</tbody>
</table>


## Remarks

Enum values are multiple of 2, so we can combine them when quering the database.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

