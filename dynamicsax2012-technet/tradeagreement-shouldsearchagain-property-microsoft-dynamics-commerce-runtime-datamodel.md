---
title: TradeAgreement.ShouldSearchAgain Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShouldSearchAgain Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ShouldSearchAgain
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.shouldsearchagain(v=AX.60)
ms:contentKeyID: 49835764
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ShouldSearchAgain
dev_langs:
- CSharp
- C++
- VB
---

# ShouldSearchAgain Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether price or discount search should continue after finding this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SEARCHAGAIN")> _
Public Property ShouldSearchAgain As Boolean
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Boolean

value = instance.ShouldSearchAgain
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SEARCHAGAIN")]
public bool ShouldSearchAgain { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SEARCHAGAIN")]
public:
property bool ShouldSearchAgain {
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

