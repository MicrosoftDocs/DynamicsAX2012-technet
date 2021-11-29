---
title: Product.ProductNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.productnumber(v=AX.60)
ms:contentKeyID: 62208731
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductNumber
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
<DataMemberAttribute> _
<ColumnAttribute("DISPLAYPRODUCTNUMBER")> _
Public Property ProductNumber As String
    Get
    Set
'Usage
Dim instance As Product
Dim value As String

value = instance.ProductNumber

instance.ProductNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISPLAYPRODUCTNUMBER")]
public string ProductNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISPLAYPRODUCTNUMBER")]
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

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

