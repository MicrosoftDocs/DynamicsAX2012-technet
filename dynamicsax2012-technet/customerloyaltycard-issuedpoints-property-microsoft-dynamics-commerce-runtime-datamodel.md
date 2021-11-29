---
title: CustomerLoyaltyCard.IssuedPoints Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IssuedPoints Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerLoyaltyCard.IssuedPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customerloyaltycard.issuedpoints(v=AX.60)
ms:contentKeyID: 49825254
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerLoyaltyCard.IssuedPoints
dev_langs:
- CSharp
- C++
- VB
---

# IssuedPoints Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the issued points.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISSUEDPOINTS")> _
<DataMemberAttribute> _
Public Property IssuedPoints As Decimal
    Get
    Friend Set
'Usage
Dim instance As CustomerLoyaltyCard
Dim value As Decimal

value = instance.IssuedPoints
```

``` csharp
[ColumnAttribute("ISSUEDPOINTS")]
[DataMemberAttribute]
public decimal IssuedPoints { get; internal set; }
```

``` c++
[ColumnAttribute(L"ISSUEDPOINTS")]
[DataMemberAttribute]
public:
property Decimal IssuedPoints {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CustomerLoyaltyCard Class](customerloyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

