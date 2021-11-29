---
title: Product.UnitsOfMeasureSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitsOfMeasureSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.UnitsOfMeasureSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.unitsofmeasuresymbol(v=AX.60)
ms:contentKeyID: 62212162
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.UnitsOfMeasureSymbol
dev_langs:
- CSharp
- C++
- VB
---

# UnitsOfMeasureSymbol Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the supported list of unit of measure symbols of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitsOfMeasureSymbol As ICollection(Of String)
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As ICollection(Of String)

value = instance.UnitsOfMeasureSymbol
```

``` csharp
[DataMemberAttribute]
public ICollection<string> UnitsOfMeasureSymbol { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<String^>^ UnitsOfMeasureSymbol {
    ICollection<String^>^ get ();
    internal: void set (ICollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

