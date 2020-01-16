---
title: ItemUnitConversion.Equals Method (ItemUnitConversion) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (ItemUnitConversion)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion.Equals(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemunitconversion.equals(v=AX.60)
ms:contentKeyID: 49852365
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (ItemUnitConversion)

Indicates whether the current object is equal to another object of the same type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As ItemUnitConversion _
) As Boolean
'Usage
Dim instance As ItemUnitConversion
Dim other As ItemUnitConversion
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    ItemUnitConversion other
)
```

``` c++
public:
virtual bool Equals(
    ItemUnitConversion^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnitConversion](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true the current object is equal to the other parameter; otherwise, false.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[ItemUnitConversion Class](itemunitconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](itemunitconversion-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

