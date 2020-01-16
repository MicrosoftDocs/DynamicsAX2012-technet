---
title: ProductPrice.CustomerContextualPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerContextualPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.CustomerContextualPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productprice.customercontextualprice(v=AX.60)
ms:contentKeyID: 62206587
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.CustomerContextualPrice
dev_langs:
- CSharp
- C++
- VB
---

# CustomerContextualPrice Property

Gets or sets the customer contextual price for price check.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerContextualPrice As Decimal
    Get
    Set
'Usage
Dim instance As ProductPrice
Dim value As Decimal

value = instance.CustomerContextualPrice

instance.CustomerContextualPrice = value
```

``` csharp
[DataMemberAttribute]
public decimal CustomerContextualPrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal CustomerContextualPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

This is the price in cutomer context and contains price group/discount information.

## See Also

#### Reference

[ProductPrice Class](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

