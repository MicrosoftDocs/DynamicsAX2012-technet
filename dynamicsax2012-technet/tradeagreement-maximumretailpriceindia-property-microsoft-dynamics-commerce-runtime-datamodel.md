---
title: TradeAgreement.MaximumRetailPriceIndia Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumRetailPriceIndia Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.MaximumRetailPriceIndia
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.maximumretailpriceindia(v=AX.60)
ms:contentKeyID: 62204323
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.MaximumRetailPriceIndia
dev_langs:
- CSharp
- C++
- VB
---

# MaximumRetailPriceIndia Property

Gets the maximum retail price (if any) set on this trade agreement. This is an India field.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MAXIMUMRETAILPRICEINDIA")> _
Public Property MaximumRetailPriceIndia As Decimal
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As Decimal

value = instance.MaximumRetailPriceIndia
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MAXIMUMRETAILPRICEINDIA")]
public decimal MaximumRetailPriceIndia { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MAXIMUMRETAILPRICEINDIA")]
public:
property Decimal MaximumRetailPriceIndia {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

