---
title: LoyaltyCardTier.TierId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TierId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTier.TierId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtier.tierid(v=AX.60)
ms:contentKeyID: 62211138
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTier.TierId
dev_langs:
- CSharp
- C++
- VB
---

# TierId Property

Gets the readable identifier of the loyalty tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TIERID")> _
<DataMemberAttribute> _
Public Property TierId As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTier
Dim value As String

value = instance.TierId
```

``` csharp
[ColumnAttribute("TIERID")]
[DataMemberAttribute]
public string TierId { get; internal set; }
```

``` c++
[ColumnAttribute(L"TIERID")]
[DataMemberAttribute]
public:
property String^ TierId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTier Class](loyaltycardtier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

