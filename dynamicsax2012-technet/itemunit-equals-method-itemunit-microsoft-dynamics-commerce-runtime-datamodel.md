---
title: ItemUnit.Equals Method (ItemUnit) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (ItemUnit)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit.Equals(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemunit.equals(v=AX.60)
ms:contentKeyID: 49832986
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (ItemUnit)

Indicates whether the current object is equal to another object of the same type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As ItemUnit _
) As Boolean
'Usage
Dim instance As ItemUnit
Dim other As ItemUnit
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    ItemUnit other
)
```

``` c++
public:
virtual bool Equals(
    ItemUnit^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if the current object is equal to the other parameter; otherwise, false.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[ItemUnit Class](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](itemunit-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

