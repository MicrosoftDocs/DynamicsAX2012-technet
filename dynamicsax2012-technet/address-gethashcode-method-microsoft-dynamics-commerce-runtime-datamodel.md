---
title: Address.GetHashCode Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetHashCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.GetHashCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.gethashcode(v=AX.60)
ms:contentKeyID: 49831744
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.GetHashCode
dev_langs:
- CSharp
- C++
- VB
---

# GetHashCode Method

Returns a hash code for this instance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function GetHashCode As Integer
'Usage
Dim instance As Address
Dim returnValue As Integer

returnValue = instance.GetHashCode()
```

``` csharp
public override int GetHashCode()
```

``` c++
public:
virtual int GetHashCode() override
```

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

