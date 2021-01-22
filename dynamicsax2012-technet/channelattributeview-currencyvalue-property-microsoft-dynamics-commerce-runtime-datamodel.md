---
title: ChannelAttributeView.CurrencyValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrencyValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.CurrencyValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelattributeview.currencyvalue(v=AX.60)
ms:contentKeyID: 65321585
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.CurrencyValue
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyValue Property

Gets the currency value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CURRENCYVALUE")> _
Public ReadOnly Property CurrencyValue As Decimal
    Get
'Usage
Dim instance As ChannelAttributeView
Dim value As Decimal

value = instance.CurrencyValue
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CURRENCYVALUE")]
public decimal CurrencyValue { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CURRENCYVALUE")]
public:
property Decimal CurrencyValue {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ChannelAttributeView Class](channelattributeview-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

