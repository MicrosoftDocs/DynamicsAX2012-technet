---
title: LoyaltySchemeLineEarn.FromActivityAmountCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromActivityAmountCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromActivityAmountCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.fromactivityamountcurrency(v=AX.60)
ms:contentKeyID: 62207849
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromActivityAmountCurrency
dev_langs:
- CSharp
- C++
- VB
---

# FromActivityAmountCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the currency of the activity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FROMACTIVITYAMOUNTCURRENCY")> _
Public Property FromActivityAmountCurrency As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As String

value = instance.FromActivityAmountCurrency
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FROMACTIVITYAMOUNTCURRENCY")]
public string FromActivityAmountCurrency { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FROMACTIVITYAMOUNTCURRENCY")]
public:
property String^ FromActivityAmountCurrency {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

