---
title: DeliveryOption.Equals Method (DeliveryOption) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (DeliveryOption)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.Equals(Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deliveryoption.equals(v=AX.60)
ms:contentKeyID: 49822326
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (DeliveryOption)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the current object is equal to another object of the same type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As DeliveryOption _
) As Boolean
'Usage
Dim instance As DeliveryOption
Dim other As DeliveryOption
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    DeliveryOption other
)
```

``` c++
public:
virtual bool Equals(
    DeliveryOption^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A valude indicating whethre the delivery options are equal.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[DeliveryOption Class](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](deliveryoption-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

