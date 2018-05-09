---
title: CustomerLoyaltyCard.ExpiredPoints Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpiredPoints Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerLoyaltyCard.ExpiredPoints
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customerloyaltycard.expiredpoints(v=AX.60)
ms:contentKeyID: 49852608
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerLoyaltyCard.ExpiredPoints
dev_langs:
- CSharp
- C++
- VB
---

# ExpiredPoints Property

Gets the number of expired points.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EXPIREDPOINTS")> _
<DataMemberAttribute> _
Public Property ExpiredPoints As Decimal
    Get
    Friend Set
'Usage
Dim instance As CustomerLoyaltyCard
Dim value As Decimal

value = instance.ExpiredPoints
```

``` csharp
[ColumnAttribute("EXPIREDPOINTS")]
[DataMemberAttribute]
public decimal ExpiredPoints { get; internal set; }
```

``` c++
[ColumnAttribute(L"EXPIREDPOINTS")]
[DataMemberAttribute]
public:
property Decimal ExpiredPoints {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CustomerLoyaltyCard Class](customerloyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

