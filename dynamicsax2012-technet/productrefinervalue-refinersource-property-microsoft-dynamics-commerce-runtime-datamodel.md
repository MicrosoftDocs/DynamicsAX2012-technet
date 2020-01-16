---
title: ProductRefinerValue.RefinerSource Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RefinerSource Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.RefinerSource
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinervalue.refinersource(v=AX.60)
ms:contentKeyID: 65319989
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.RefinerSource
dev_langs:
- CSharp
- C++
- VB
---

# RefinerSource Property

Gets or sets the source of the product refiner.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("REFINERSOURCE")> _
Public Property RefinerSource As ProductRefinerSource
    Get
    Set
'Usage
Dim instance As ProductRefinerValue
Dim value As ProductRefinerSource

value = instance.RefinerSource

instance.RefinerSource = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("REFINERSOURCE")]
public ProductRefinerSource RefinerSource { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"REFINERSOURCE")]
public:
property ProductRefinerSource RefinerSource {
    ProductRefinerSource get ();
    void set (ProductRefinerSource value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerSource](productrefinersource-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Represents the object that is being used as a product refiner.  

## See Also

#### Reference

[ProductRefinerValue Class](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

