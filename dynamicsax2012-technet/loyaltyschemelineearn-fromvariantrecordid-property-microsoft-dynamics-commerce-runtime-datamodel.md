---
title: LoyaltySchemeLineEarn.FromVariantRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromVariantRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromVariantRecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.fromvariantrecordid(v=AX.60)
ms:contentKeyID: 62204535
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromVariantRecordId
dev_langs:
- CSharp
- C++
- VB
---

# FromVariantRecordId Property

Gets the record identifier of the variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("VARIANTRECID")> _
Public Property FromVariantRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As Long

value = instance.FromVariantRecordId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("VARIANTRECID")]
public long FromVariantRecordId { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"VARIANTRECID")]
public:
property long long FromVariantRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

