---
title: TradeAgreement.StyleId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StyleId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.StyleId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.styleid(v=AX.60)
ms:contentKeyID: 62206932
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.StyleId
dev_langs:
- CSharp
- C++
- VB
---

# StyleId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the style Id (if any) set on this trade agreement.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSTYLEID")> _
Public Property StyleId As String
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As String

value = instance.StyleId
```

``` csharp
[ColumnAttribute("INVENTSTYLEID")]
public string StyleId { get; internal set; }
```

``` c++
[ColumnAttribute(L"INVENTSTYLEID")]
public:
property String^ StyleId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

