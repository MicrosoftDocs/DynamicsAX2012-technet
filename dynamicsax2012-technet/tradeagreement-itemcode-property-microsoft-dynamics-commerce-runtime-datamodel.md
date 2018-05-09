---
title: TradeAgreement.ItemCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ItemCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.itemcode(v=AX.60)
ms:contentKeyID: 49831999
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.ItemCode
dev_langs:
- CSharp
- C++
- VB
---

# ItemCode Property

Gets the type of item configuration for this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ITEMCODE")> _
<DataMemberAttribute> _
Public Property ItemCode As PriceDiscountItemCode
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As PriceDiscountItemCode

value = instance.ItemCode
```

``` csharp
[ColumnAttribute("ITEMCODE")]
[DataMemberAttribute]
public PriceDiscountItemCode ItemCode { get; internal set; }
```

``` c++
[ColumnAttribute(L"ITEMCODE")]
[DataMemberAttribute]
public:
property PriceDiscountItemCode ItemCode {
    PriceDiscountItemCode get ();
    internal: void set (PriceDiscountItemCode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode](pricediscountitemcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PriceDiscountItemCode](pricediscountitemcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

