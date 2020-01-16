---
title: DiscountInvalidatedNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountInvalidatedNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountinvalidatednotification.discountinvalidatednotification(v=AX.60)
ms:contentKeyID: 65321143
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DiscountInvalidatedNotification Constructor

Initializes a new instance of the [DiscountInvalidatedNotification](discountinvalidatednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    line As SalesLine, _
    oldDiscountAmount As Decimal _
)
'Usage
Dim line As SalesLine
Dim oldDiscountAmount As Decimal

Dim instance As New DiscountInvalidatedNotification(line, oldDiscountAmount)
```

``` csharp
public DiscountInvalidatedNotification(
    SalesLine line,
    decimal oldDiscountAmount
)
```

``` c++
public:
DiscountInvalidatedNotification(
    SalesLine^ line, 
    Decimal oldDiscountAmount
)
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - oldDiscountAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[DiscountInvalidatedNotification Class](discountinvalidatednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

