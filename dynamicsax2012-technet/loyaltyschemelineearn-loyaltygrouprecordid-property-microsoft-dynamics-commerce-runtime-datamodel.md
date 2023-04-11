---
title: LoyaltySchemeLineEarn.LoyaltyGroupRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyGroupRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.LoyaltyGroupRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.loyaltygrouprecordid(v=AX.60)
ms:contentKeyID: 62212465
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.LoyaltyGroupRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyGroupRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the record identifier of the loyalty group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("LOYALTYGROUPRECID")> _
Public Property LoyaltyGroupRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As Long

value = instance.LoyaltyGroupRecordId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("LOYALTYGROUPRECID")]
public long LoyaltyGroupRecordId { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"LOYALTYGROUPRECID")]
public:
property long long LoyaltyGroupRecordId {
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

