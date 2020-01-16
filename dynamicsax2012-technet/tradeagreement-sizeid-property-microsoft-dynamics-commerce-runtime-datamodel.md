---
title: TradeAgreement.SizeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SizeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.SizeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.sizeid(v=AX.60)
ms:contentKeyID: 62203685
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.SizeId
dev_langs:
- CSharp
- C++
- VB
---

# SizeId Property

Gets the size Id (if any) set on this trade agreement.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSIZEID")> _
Public Property SizeId As String
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As String

value = instance.SizeId
```

``` csharp
[ColumnAttribute("INVENTSIZEID")]
public string SizeId { get; internal set; }
```

``` c++
[ColumnAttribute(L"INVENTSIZEID")]
public:
property String^ SizeId {
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

