---
title: ItemAvailability.AvailableQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AvailableQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.AvailableQuantity
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailability.availablequantity(v=AX.60)
ms:contentKeyID: 49829756
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.AvailableQuantity
dev_langs:
- CSharp
- C++
- VB
---

# AvailableQuantity Property

Gets or sets the available quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AVAILPHYSICAL")> _
Public Property AvailableQuantity As Decimal
    Get
    Set
'Usage
Dim instance As ItemAvailability
Dim value As Decimal

value = instance.AvailableQuantity

instance.AvailableQuantity = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AVAILPHYSICAL")]
public decimal AvailableQuantity { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AVAILPHYSICAL")]
public:
property Decimal AvailableQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ItemAvailability Class](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

