---
title: CartLineData.TaxRatePercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxRatePercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.TaxRatePercent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.taxratepercent(v=AX.60)
ms:contentKeyID: 62210506
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.TaxRatePercent
dev_langs:
- CSharp
- C++
- VB
---

# TaxRatePercent Property

Gets or sets the tax rate percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXRATEPERCENT")> _
Public Property TaxRatePercent As Decimal
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.TaxRatePercent

instance.TaxRatePercent = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXRATEPERCENT")]
public decimal TaxRatePercent { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXRATEPERCENT")]
public:
property Decimal TaxRatePercent {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The tax rate percentage.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

