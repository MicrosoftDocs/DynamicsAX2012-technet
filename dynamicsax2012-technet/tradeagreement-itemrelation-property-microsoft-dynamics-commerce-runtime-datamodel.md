---
title: TradeAgreement.ItemRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ItemRelation
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.itemrelation(v=AX.60)
ms:contentKeyID: 49842390
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ItemRelation
dev_langs:
- CSharp
- C++
- VB
---

# ItemRelation Property

Gets the item configuration identifier (could be item identifier, item group identifier, or empty).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ITEMRELATION")> _
<DataMemberAttribute> _
Public Property ItemRelation As String
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As String

value = instance.ItemRelation
```

``` csharp
[ColumnAttribute("ITEMRELATION")]
[DataMemberAttribute]
public string ItemRelation { get; internal set; }
```

``` c++
[ColumnAttribute(L"ITEMRELATION")]
[DataMemberAttribute]
public:
property String^ ItemRelation {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

