---
title: LoyaltySchemeLineEarn.ValidFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ValidFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.validfrom(v=AX.60)
ms:contentKeyID: 62206689
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ValidFrom
dev_langs:
- CSharp
- C++
- VB
---

# ValidFrom Property

Gets the start date of the valid period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("VALIDFROM")> _
Public Property ValidFrom As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As DateTimeOffset

value = instance.ValidFrom
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("VALIDFROM")]
public DateTimeOffset ValidFrom { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"VALIDFROM")]
public:
property DateTimeOffset ValidFrom {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

