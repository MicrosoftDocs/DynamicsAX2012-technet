---
title: CustomerType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customertype(v=AX.60)
ms:contentKeyID: 49836749
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerType.Organization
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerType.Person
dev_langs:
- CSharp
- C++
- VB
---

# CustomerType Enumeration

Represents the type of customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration CustomerType
'Usage
Dim instance As CustomerType
```

``` csharp
[DataContractAttribute]
public enum CustomerType
```

``` c++
[DataContractAttribute]
public enum class CustomerType
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
<td>No customer type has been defined.</td>
</tr>
<tr class="even">
<td></td>
<td>Person</td>
<td>The customer is a person.</td>
</tr>
<tr class="odd">
<td></td>
<td>Organization</td>
<td>The customer is an organization.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

