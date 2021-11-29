---
title: TradeAgreement.Currency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Currency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.Currency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.currency(v=AX.60)
ms:contentKeyID: 49832046
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.Currency
dev_langs:
- CSharp
- C++
- VB
---

# Currency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the currency this rule is defined in.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CURRENCY")> _
<DataMemberAttribute> _
Public Property Currency As String
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As String

value = instance.Currency
```

``` csharp
[ColumnAttribute("CURRENCY")]
[DataMemberAttribute]
public string Currency { get; internal set; }
```

``` c++
[ColumnAttribute(L"CURRENCY")]
[DataMemberAttribute]
public:
property String^ Currency {
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

