---
title: ProductVariant.ProductNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.ProductNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.productnumber(v=AX.60)
ms:contentKeyID: 62210133
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.ProductNumber
dev_langs:
- CSharp
- C++
- VB
---

# ProductNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the unique product number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISPLAYPRODUCTNUMBER")> _
<DataMemberAttribute> _
Public Property ProductNumber As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.ProductNumber

instance.ProductNumber = value
```

``` csharp
[ColumnAttribute("DISPLAYPRODUCTNUMBER")]
[DataMemberAttribute]
public string ProductNumber { get; set; }
```

``` c++
[ColumnAttribute(L"DISPLAYPRODUCTNUMBER")]
[DataMemberAttribute]
public:
property String^ ProductNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

