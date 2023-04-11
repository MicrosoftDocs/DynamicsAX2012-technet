---
title: PaymentCard.Equals Method (PaymentCard) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (PaymentCard)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.Equals(Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcard.equals(v=AX.60)
ms:contentKeyID: 62207791
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (PaymentCard)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the current object is equal to another object of the same type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As PaymentCard _
) As Boolean
'Usage
Dim instance As PaymentCard
Dim other As PaymentCard
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    PaymentCard other
)
```

``` c++
public:
virtual bool Equals(
    PaymentCard^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the paymentcards are equal.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[PaymentCard Class](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](paymentcard-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

