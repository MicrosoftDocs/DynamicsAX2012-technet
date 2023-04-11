---
title: TaxableItem.SalesOrderUnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesOrderUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.SalesOrderUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.salesorderunitofmeasure(v=AX.60)
ms:contentKeyID: 49851437
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.SalesOrderUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrderUnitOfMeasure Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

//The active item sale unit of measurement (based upon UOM set for the item by the user)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("UNITOFMEASURESYMBOL")> _
Public Property SalesOrderUnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As String

value = instance.SalesOrderUnitOfMeasure

instance.SalesOrderUnitOfMeasure = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("UNITOFMEASURESYMBOL")]
public string SalesOrderUnitOfMeasure { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"UNITOFMEASURESYMBOL")]
public:
property String^ SalesOrderUnitOfMeasure {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

