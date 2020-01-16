---
title: Product.IsMasterProduct Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsMasterProduct Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IsMasterProduct
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.ismasterproduct(v=AX.60)
ms:contentKeyID: 62203226
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IsMasterProduct
dev_langs:
- CSharp
- C++
- VB
---

# IsMasterProduct Property

Gets a value indicating whether this is a master or standalone product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property IsMasterProduct As Boolean
    Get
    Set
'Usage
Dim instance As Product
Dim value As Boolean

value = instance.IsMasterProduct

instance.IsMasterProduct = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public bool IsMasterProduct { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property bool IsMasterProduct {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

