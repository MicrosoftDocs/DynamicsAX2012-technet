---
title: DiscountInvalidatedNotification.NewDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NewDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification.NewDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountinvalidatednotification.newdiscountamount(v=AX.60)
ms:contentKeyID: 65322223
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification.NewDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# NewDiscountAmount Property

Gets the new discount amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NewDiscountAmount As Decimal
    Get
    Private Set
'Usage
Dim instance As DiscountInvalidatedNotification
Dim value As Decimal

value = instance.NewDiscountAmount
```

``` csharp
[DataMemberAttribute]
public decimal NewDiscountAmount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal NewDiscountAmount {
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

