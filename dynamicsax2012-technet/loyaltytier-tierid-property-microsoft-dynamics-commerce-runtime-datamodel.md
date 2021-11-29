---
title: LoyaltyTier.TierId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TierId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTier.TierId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltytier.tierid(v=AX.60)
ms:contentKeyID: 62208128
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyTier.TierId
dev_langs:
- CSharp
- C++
- VB
---

# TierId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the readable identifier of the loyalty tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TIERID")> _
Public Property TierId As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltyTier
Dim value As String

value = instance.TierId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TIERID")]
public string TierId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TIERID")]
public:
property String^ TierId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyTier Class](loyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

