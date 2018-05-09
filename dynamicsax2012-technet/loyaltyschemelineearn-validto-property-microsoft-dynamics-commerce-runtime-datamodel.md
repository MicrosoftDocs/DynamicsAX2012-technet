---
title: LoyaltySchemeLineEarn.ValidTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ValidTo
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.validto(v=AX.60)
ms:contentKeyID: 62202564
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ValidTo
dev_langs:
- CSharp
- C++
- VB
---

# ValidTo Property

Gets the end date of the valid period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("VALIDTO")> _
Public Property ValidTo As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As DateTimeOffset

value = instance.ValidTo
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("VALIDTO")]
public DateTimeOffset ValidTo { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"VALIDTO")]
public:
property DateTimeOffset ValidTo {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

