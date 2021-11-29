---
title: LoyaltyCardTier.ValidTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTier.ValidTo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtier.validto(v=AX.60)
ms:contentKeyID: 62203980
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTier.ValidTo
dev_langs:
- CSharp
- C++
- VB
---

# ValidTo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the end date of the valid period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VALIDTO")> _
Public Property ValidTo As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTier
Dim value As DateTimeOffset

value = instance.ValidTo
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VALIDTO")]
public DateTimeOffset ValidTo { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VALIDTO")]
public:
property DateTimeOffset ValidTo {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTier Class](loyaltycardtier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

