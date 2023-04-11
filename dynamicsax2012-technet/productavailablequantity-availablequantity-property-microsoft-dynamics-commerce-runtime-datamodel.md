---
title: ProductAvailableQuantity.AvailableQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AvailableQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAvailableQuantity.AvailableQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productavailablequantity.availablequantity(v=AX.60)
ms:contentKeyID: 62214426
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAvailableQuantity.AvailableQuantity
dev_langs:
- CSharp
- C++
- VB
---

# AvailableQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the available quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AVAILPHYSICAL")> _
<DataMemberAttribute> _
Public Property AvailableQuantity As Decimal
    Get
    Set
'Usage
Dim instance As ProductAvailableQuantity
Dim value As Decimal

value = instance.AvailableQuantity

instance.AvailableQuantity = value
```

``` csharp
[ColumnAttribute("AVAILPHYSICAL")]
[DataMemberAttribute]
public decimal AvailableQuantity { get; set; }
```

``` c++
[ColumnAttribute(L"AVAILPHYSICAL")]
[DataMemberAttribute]
public:
property Decimal AvailableQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ProductAvailableQuantity Class](productavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

