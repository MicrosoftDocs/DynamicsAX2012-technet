---
title: LoyaltySchemeLineEarn.FromActivityType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromActivityType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromActivityType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.fromactivitytype(v=AX.60)
ms:contentKeyID: 62212192
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.FromActivityType
dev_langs:
- CSharp
- C++
- VB
---

# FromActivityType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the loyalty activity type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FROMACTIVITYTYPE")> _
Public Property FromActivityType As LoyaltyActivityType
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As LoyaltyActivityType

value = instance.FromActivityType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FROMACTIVITYTYPE")]
public LoyaltyActivityType FromActivityType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FROMACTIVITYTYPE")]
public:
property LoyaltyActivityType FromActivityType {
    LoyaltyActivityType get ();
    internal: void set (LoyaltyActivityType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyActivityType](loyaltyactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyActivityType](loyaltyactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

