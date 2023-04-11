---
title: LoyaltySchemeLineRedeem.ToProductRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToProductRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToProductRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.toproductrecordid(v=AX.60)
ms:contentKeyID: 62212333
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToProductRecordId
dev_langs:
- CSharp
- C++
- VB
---

# ToProductRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the record identifier of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRODUCTRECID")> _
<IgnoreDataMemberAttribute> _
Public Property ToProductRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As Long

value = instance.ToProductRecordId
```

``` csharp
[ColumnAttribute("PRODUCTRECID")]
[IgnoreDataMemberAttribute]
public long ToProductRecordId { get; internal set; }
```

``` c++
[ColumnAttribute(L"PRODUCTRECID")]
[IgnoreDataMemberAttribute]
public:
property long long ToProductRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

