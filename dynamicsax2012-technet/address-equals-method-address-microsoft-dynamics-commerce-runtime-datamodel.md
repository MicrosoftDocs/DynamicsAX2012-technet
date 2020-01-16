---
title: Address.Equals Method (Address) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (Address)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Equals(Microsoft.Dynamics.Commerce.Runtime.DataModel.Address)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.equals(v=AX.60)
ms:contentKeyID: 49843558
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (Address)

Indicates whether the current object is equal to another object of the same type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As Address _
) As Boolean
'Usage
Dim instance As Address
Dim other As Address
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    Address other
)
```

``` c++
public:
virtual bool Equals(
    Address^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the addresses are equal.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](address-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

