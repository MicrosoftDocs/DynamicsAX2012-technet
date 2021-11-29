---
title: RetailDiscount.MixAndMatchDealPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchDealPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchDealPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.mixandmatchdealprice(v=AX.60)
ms:contentKeyID: 62204791
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchDealPrice
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchDealPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the deal price for mix and match set if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DEALPRICEVALUE")> _
<DataMemberAttribute> _
Public Property MixAndMatchDealPrice As Decimal
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Decimal

value = instance.MixAndMatchDealPrice

instance.MixAndMatchDealPrice = value
```

``` csharp
[ColumnAttribute("DEALPRICEVALUE")]
[DataMemberAttribute]
public decimal MixAndMatchDealPrice { get; set; }
```

``` c++
[ColumnAttribute(L"DEALPRICEVALUE")]
[DataMemberAttribute]
public:
property Decimal MixAndMatchDealPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

