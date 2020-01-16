---
title: Product.GetProductActiveCatalogs Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetProductActiveCatalogs Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetProductActiveCatalogs
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.getproductactivecatalogs(v=AX.60)
ms:contentKeyID: 62206152
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductActiveCatalogs Method

Returns the list of active catalog ids which feature this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductActiveCatalogs As ReadOnlyCollection(Of ProductCatalog)
'Usage
Dim instance As Product
Dim returnValue As ReadOnlyCollection(Of ProductCatalog)

returnValue = instance.GetProductActiveCatalogs()
```

``` csharp
public ReadOnlyCollection<ProductCatalog> GetProductActiveCatalogs()
```

``` c++
public:
ReadOnlyCollection<ProductCatalog^>^ GetProductActiveCatalogs()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A list of active catalog ids which include this product.  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetProductActiveCatalogs Overload](product-getproductactivecatalogs-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

