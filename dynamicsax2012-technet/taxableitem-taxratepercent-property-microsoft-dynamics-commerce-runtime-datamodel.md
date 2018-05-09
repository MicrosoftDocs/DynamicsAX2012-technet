---
title: TaxableItem.TaxRatePercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxRatePercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.TaxRatePercent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.taxratepercent(v=AX.60)
ms:contentKeyID: 49832333
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.TaxRatePercent
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
Public Property TaxRatePercent As Decimal
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As Decimal

value = instance.TaxRatePercent

instance.TaxRatePercent = value
```

``` csharp
[DataMemberAttribute]
public decimal TaxRatePercent { get; set; }
```

``` c++
[DataMemberAttribute]
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

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

