---
title: CartLineData.UnitOfMeasureSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitOfMeasureSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.UnitOfMeasureSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.unitofmeasuresymbol(v=AX.60)
ms:contentKeyID: 62211741
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.UnitOfMeasureSymbol
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasureSymbol Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the symbol of unit of measure of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("UNITOFMEASURESYMBOL")> _
<DataMemberAttribute> _
Public Property UnitOfMeasureSymbol As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.UnitOfMeasureSymbol

instance.UnitOfMeasureSymbol = value
```

``` csharp
[ColumnAttribute("UNITOFMEASURESYMBOL")]
[DataMemberAttribute]
public string UnitOfMeasureSymbol { get; set; }
```

``` c++
[ColumnAttribute(L"UNITOFMEASURESYMBOL")]
[DataMemberAttribute]
public:
property String^ UnitOfMeasureSymbol {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The requested unit of measure.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

