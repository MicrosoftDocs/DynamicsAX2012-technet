---
title: ItemQuantity.Equals Method (ItemQuantity) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (ItemQuantity)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity.Equals(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemquantity.equals(v=AX.60)
ms:contentKeyID: 49827897
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (ItemQuantity)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the current object is equal to another object of the same type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As ItemQuantity _
) As Boolean
'Usage
Dim instance As ItemQuantity
Dim other As ItemQuantity
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    ItemQuantity other
)
```

``` c++
public:
virtual bool Equals(
    ItemQuantity^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if the current object is equal to the other parameter; otherwise, false.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[ItemQuantity Class](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](itemquantity-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

