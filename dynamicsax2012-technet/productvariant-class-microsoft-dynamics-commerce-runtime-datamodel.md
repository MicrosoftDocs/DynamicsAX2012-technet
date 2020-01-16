---
title: ProductVariant Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariant Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant(v=AX.60)
ms:contentKeyID: 62211965
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariant Class

Represents a variant of a product with size, color, style, and config dimensions.

Also has information about the legal entity the variant is in.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class ProductVariant _
    Inherits CommerceEntity
'Usage
Dim instance As ProductVariant
```

``` csharp
[DataContractAttribute]
public class ProductVariant : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class ProductVariant : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

