---
title: ProductSearchResult Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductSearchResult Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchresult(v=AX.60)
ms:contentKeyID: 62213171
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult
dev_langs:
- CSharp
- C++
- VB
---

# ProductSearchResult Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the response to a query for Product objects.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class ProductSearchResult _
    Inherits CommerceEntitySearchResult(Of Product)
'Usage
Dim instance As ProductSearchResult
```

``` csharp
[DataContractAttribute]
public sealed class ProductSearchResult : CommerceEntitySearchResult<Product>
```

``` c++
[DataContractAttribute]
public ref class ProductSearchResult sealed : public CommerceEntitySearchResult<Product^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearch](commerceentitysearch-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearchResult](commerceentitysearchresult-t-class-microsoft-dynamics-commerce-runtime-datamodel.md)\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

