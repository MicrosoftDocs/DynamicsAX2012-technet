---
title: TradeAgreement.ConfigId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConfigId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ConfigId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.configid(v=AX.60)
ms:contentKeyID: 62211635
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ConfigId
dev_langs:
- CSharp
- C++
- VB
---

# ConfigId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the configuration Id (if any) set on this trade agreement.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CONFIGID")> _
Public Property ConfigId As String
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As String

value = instance.ConfigId
```

``` csharp
[ColumnAttribute("CONFIGID")]
public string ConfigId { get; internal set; }
```

``` c++
[ColumnAttribute(L"CONFIGID")]
public:
property String^ ConfigId {
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

