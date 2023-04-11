---
title: Product.ProductName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.productname(v=AX.60)
ms:contentKeyID: 62214175
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ProductName
dev_langs:
- CSharp
- C++
- VB
---

# ProductName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the name of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductName As String
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As String

value = instance.ProductName
```

``` csharp
[DataMemberAttribute]
public string ProductName { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ProductName {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name of the product.  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

