---
title: LoyaltySchemeLineEarn.FromProductRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromProductRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromProductRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.fromproductrecordid(v=AX.60)
ms:contentKeyID: 62212164
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromProductRecordId
dev_langs:
- CSharp
- C++
- VB
---

# FromProductRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the record identifier of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("PRODUCTRECID")> _
Public Property FromProductRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As Long

value = instance.FromProductRecordId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("PRODUCTRECID")]
public long FromProductRecordId { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"PRODUCTRECID")]
public:
property long long FromProductRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

