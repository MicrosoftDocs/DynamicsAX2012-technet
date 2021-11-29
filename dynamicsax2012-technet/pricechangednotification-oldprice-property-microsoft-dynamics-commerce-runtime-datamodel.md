---
title: PriceChangedNotification.OldPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OldPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceChangedNotification.OldPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pricechangednotification.oldprice(v=AX.60)
ms:contentKeyID: 65322676
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceChangedNotification.OldPrice
dev_langs:
- CSharp
- C++
- VB
---

# OldPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the old price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OldPrice As Decimal
    Get
    Private Set
'Usage
Dim instance As PriceChangedNotification
Dim value As Decimal

value = instance.OldPrice
```

``` csharp
[DataMemberAttribute]
public decimal OldPrice { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal OldPrice {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PriceChangedNotification Class](pricechangednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

