---
title: LoyaltySchemeLineRedeem.ToVariantRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToVariantRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToVariantRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.tovariantrecordid(v=AX.60)
ms:contentKeyID: 62204753
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToVariantRecordId
dev_langs:
- CSharp
- C++
- VB
---

# ToVariantRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the record identifier of the variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("VARIANTRECID")> _
Public Property ToVariantRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As Long

value = instance.ToVariantRecordId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("VARIANTRECID")]
public long ToVariantRecordId { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"VARIANTRECID")]
public:
property long long ToVariantRecordId {
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

