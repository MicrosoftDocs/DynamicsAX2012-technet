---
title: ProductAvailableQuantity.UnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAvailableQuantity.UnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productavailablequantity.unitofmeasure(v=AX.60)
ms:contentKeyID: 62214961
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAvailableQuantity.UnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasure Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit of measure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("UNITID")> _
<DataMemberAttribute> _
Public Property UnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As ProductAvailableQuantity
Dim value As String

value = instance.UnitOfMeasure

instance.UnitOfMeasure = value
```

``` csharp
[ColumnAttribute("UNITID")]
[DataMemberAttribute]
public string UnitOfMeasure { get; set; }
```

``` c++
[ColumnAttribute(L"UNITID")]
[DataMemberAttribute]
public:
property String^ UnitOfMeasure {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductAvailableQuantity Class](productavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

