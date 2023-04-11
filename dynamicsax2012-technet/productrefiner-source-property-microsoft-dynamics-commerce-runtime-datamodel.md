---
title: ProductRefiner.Source Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Source Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.Source
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.source(v=AX.60)
ms:contentKeyID: 65319446
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.Source
dev_langs:
- CSharp
- C++
- VB
---

# Source Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the source of the product refiner.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SOURCE")> _
<IgnoreDataMemberAttribute> _
Public Property Source As ProductRefinerSource
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As ProductRefinerSource

value = instance.Source

instance.Source = value
```

``` csharp
[ColumnAttribute("SOURCE")]
[IgnoreDataMemberAttribute]
public ProductRefinerSource Source { get; set; }
```

``` c++
[ColumnAttribute(L"SOURCE")]
[IgnoreDataMemberAttribute]
public:
property ProductRefinerSource Source {
    ProductRefinerSource get ();
    void set (ProductRefinerSource value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerSource](productrefinersource-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Represents the object that is being used as a product refiner.  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

