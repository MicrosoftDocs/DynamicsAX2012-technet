---
title: ProductPrice.TradeAgreementPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TradeAgreementPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.TradeAgreementPrice
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productprice.tradeagreementprice(v=AX.60)
ms:contentKeyID: 62211576
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.TradeAgreementPrice
dev_langs:
- CSharp
- C++
- VB
---

# TradeAgreementPrice Property

Gets or sets the trade agreement price for the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TRADEAGREEMENTPRICE")> _
<DataMemberAttribute> _
Public Property TradeAgreementPrice As Decimal
    Get
    Set
'Usage
Dim instance As ProductPrice
Dim value As Decimal

value = instance.TradeAgreementPrice

instance.TradeAgreementPrice = value
```

``` csharp
[ColumnAttribute("TRADEAGREEMENTPRICE")]
[DataMemberAttribute]
public decimal TradeAgreementPrice { get; set; }
```

``` c++
[ColumnAttribute(L"TRADEAGREEMENTPRICE")]
[DataMemberAttribute]
public:
property Decimal TradeAgreementPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

If no trade agreements found, this is the BasePrice.

## See Also

#### Reference

[ProductPrice Class](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

