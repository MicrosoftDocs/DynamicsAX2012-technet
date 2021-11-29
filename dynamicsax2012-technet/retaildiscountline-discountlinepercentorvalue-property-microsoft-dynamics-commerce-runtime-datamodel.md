---
title: RetailDiscountLine.DiscountLinePercentOrValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLinePercentOrValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.DiscountLinePercentOrValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountline.discountlinepercentorvalue(v=AX.60)
ms:contentKeyID: 62214807
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.DiscountLinePercentOrValue
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLinePercentOrValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the percent or amount value from the discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTPERCENTORVALUE")> _
<DataMemberAttribute> _
Public Property DiscountLinePercentOrValue As Decimal
    Get
    Set
'Usage
Dim instance As RetailDiscountLine
Dim value As Decimal

value = instance.DiscountLinePercentOrValue

instance.DiscountLinePercentOrValue = value
```

``` csharp
[ColumnAttribute("DISCOUNTPERCENTORVALUE")]
[DataMemberAttribute]
public decimal DiscountLinePercentOrValue { get; set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTPERCENTORVALUE")]
[DataMemberAttribute]
public:
property Decimal DiscountLinePercentOrValue {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscountLine Class](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

