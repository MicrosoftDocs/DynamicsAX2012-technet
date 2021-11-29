---
title: LoyaltySchemeLineRedeem.ToRewardAmountCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardAmountCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToRewardAmountCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.torewardamountcurrency(v=AX.60)
ms:contentKeyID: 62208066
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToRewardAmountCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardAmountCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the currency of the reward if the reward measured by amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TOREWARDAMOUNTCURRENCY")> _
Public Property ToRewardAmountCurrency As String
    Get
    Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As String

value = instance.ToRewardAmountCurrency

instance.ToRewardAmountCurrency = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TOREWARDAMOUNTCURRENCY")]
public string ToRewardAmountCurrency { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TOREWARDAMOUNTCURRENCY")]
public:
property String^ ToRewardAmountCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

