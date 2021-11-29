---
title: ItemBarcode.Quantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Quantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.Quantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.quantity(v=AX.60)
ms:contentKeyID: 62203480
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.Quantity
dev_langs:
- CSharp
- C++
- VB
---

# Quantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Item's quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QTY")> _
<DataMemberAttribute> _
Public Property Quantity As Decimal
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As Decimal

value = instance.Quantity
```

``` csharp
[ColumnAttribute("QTY")]
[DataMemberAttribute]
public decimal Quantity { get; internal set; }
```

``` c++
[ColumnAttribute(L"QTY")]
[DataMemberAttribute]
public:
property Decimal Quantity {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ItemBarcode Class](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

