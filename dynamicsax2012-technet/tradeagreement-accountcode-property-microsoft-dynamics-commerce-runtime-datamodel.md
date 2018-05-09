---
title: TradeAgreement.AccountCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.AccountCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.accountcode(v=AX.60)
ms:contentKeyID: 49833435
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.AccountCode
dev_langs:
- CSharp
- C++
- VB
---

# AccountCode Property

Gets the type of customer configuration for this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ACCOUNTCODE")> _
Public Property AccountCode As PriceDiscountAccountCode
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As PriceDiscountAccountCode

value = instance.AccountCode
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ACCOUNTCODE")]
public PriceDiscountAccountCode AccountCode { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ACCOUNTCODE")]
public:
property PriceDiscountAccountCode AccountCode {
    PriceDiscountAccountCode get ();
    internal: void set (PriceDiscountAccountCode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode](pricediscountaccountcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PriceDiscountAccountCode](pricediscountaccountcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

