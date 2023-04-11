---
title: ChannelAttributeView.CurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.CurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelattributeview.currencycode(v=AX.60)
ms:contentKeyID: 65320659
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.CurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the currency code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CURRENCYCODE")> _
Public ReadOnly Property CurrencyCode As String
    Get
'Usage
Dim instance As ChannelAttributeView
Dim value As String

value = instance.CurrencyCode
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CURRENCYCODE")]
public string CurrencyCode { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CURRENCYCODE")]
public:
property String^ CurrencyCode {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelAttributeView Class](channelattributeview-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

