---
title: TradeAgreement.ShouldIncludeMarkup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShouldIncludeMarkup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ShouldIncludeMarkup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.shouldincludemarkup(v=AX.60)
ms:contentKeyID: 49825753
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ShouldIncludeMarkup
dev_langs:
- CSharp
- C++
- VB
---

# ShouldIncludeMarkup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether markup should be included in the price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ALLOCATEMARKUP")> _
Public Property ShouldIncludeMarkup As Boolean
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Boolean

value = instance.ShouldIncludeMarkup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ALLOCATEMARKUP")]
public bool ShouldIncludeMarkup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ALLOCATEMARKUP")]
public:
property bool ShouldIncludeMarkup {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

