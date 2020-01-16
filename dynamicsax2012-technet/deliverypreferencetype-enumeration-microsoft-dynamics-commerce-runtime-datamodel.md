---
title: DeliveryPreferenceType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryPreferenceType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deliverypreferencetype(v=AX.60)
ms:contentKeyID: 65318425
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType.DeliverItemsIndividually
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType.ElectronicDelivery
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType.PickupFromStore
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType.ShipToAddress
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryPreferenceType Enumeration

Defines the available delivery preference types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration DeliveryPreferenceType
'Usage
Dim instance As DeliveryPreferenceType
```

``` csharp
[DataContractAttribute]
public enum DeliveryPreferenceType
```

``` c++
[DataContractAttribute]
public enum class DeliveryPreferenceType
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
<td>Represents the case when the delivery preference type has not been set.</td>
</tr>
<tr class="even">
<td></td>
<td>ShipToAddress</td>
<td>Represents the case when the item can be shipped to an address.</td>
</tr>
<tr class="odd">
<td></td>
<td>PickupFromStore</td>
<td>Represents the case when the item can be picked up from a store.</td>
</tr>
<tr class="even">
<td></td>
<td>ElectronicDelivery</td>
<td>Represents the case when the item can be electronically delivered over e-mail.</td>
</tr>
<tr class="odd">
<td></td>
<td>DeliverItemsIndividually</td>
<td>Represents the case when the items can be delivered individually. Applicable only to cart header level delivery preferences.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

