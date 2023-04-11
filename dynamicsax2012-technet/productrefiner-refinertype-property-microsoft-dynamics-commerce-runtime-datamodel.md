---
title: ProductRefiner.RefinerType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RefinerType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.RefinerType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.refinertype(v=AX.60)
ms:contentKeyID: 65319851
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.RefinerType
dev_langs:
- CSharp
- C++
- VB
---

# RefinerType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the refiner indicating it's usage style.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("DISPLAYOPTION")> _
Public Property RefinerType As RefinerType
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As RefinerType

value = instance.RefinerType

instance.RefinerType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("DISPLAYOPTION")]
public RefinerType RefinerType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"DISPLAYOPTION")]
public:
property RefinerType RefinerType {
    RefinerType get ();
    void set (RefinerType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RefinerType](refinertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RefinerType](refinertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

