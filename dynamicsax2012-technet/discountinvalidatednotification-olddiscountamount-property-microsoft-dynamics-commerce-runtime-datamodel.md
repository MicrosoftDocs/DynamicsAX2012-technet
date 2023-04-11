---
title: DiscountInvalidatedNotification.OldDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OldDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification.OldDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountinvalidatednotification.olddiscountamount(v=AX.60)
ms:contentKeyID: 65315695
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification.OldDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# OldDiscountAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the old discount amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OldDiscountAmount As Decimal
    Get
    Private Set
'Usage
Dim instance As DiscountInvalidatedNotification
Dim value As Decimal

value = instance.OldDiscountAmount
```

``` csharp
[DataMemberAttribute]
public decimal OldDiscountAmount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal OldDiscountAmount {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[DiscountInvalidatedNotification Class](discountinvalidatednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

