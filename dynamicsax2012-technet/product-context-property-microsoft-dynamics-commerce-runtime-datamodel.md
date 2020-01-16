---
title: Product.Context Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Context Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.Context
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.context(v=AX.60)
ms:contentKeyID: 62213088
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.Context
dev_langs:
- CSharp
- C++
- VB
---

# Context Property

Gets or sets the Retail context of this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Context As ProjectionDomain
    Get
    Set
'Usage
Dim instance As Product
Dim value As ProjectionDomain

value = instance.Context

instance.Context = value
```

``` csharp
[DataMemberAttribute]
public ProjectionDomain Context { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ProjectionDomain^ Context {
    ProjectionDomain^ get ();
    void set (ProjectionDomain^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The Retail context of this product - primarily, the catalog and channel through which the product is accessed.  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

