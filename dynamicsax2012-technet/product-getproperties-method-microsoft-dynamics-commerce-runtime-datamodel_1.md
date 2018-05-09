---
title: Product.GetProperties Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetProperties Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.getproperties(v=AX.60)
ms:contentKeyID: 62213237
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProperties Method

Enumerates the product's attributes, together with their default values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetProperties As ReadOnlyCollection(Of ProductProperty)
'Usage
Dim instance As Product
Dim returnValue As ReadOnlyCollection(Of ProductProperty)

returnValue = instance.GetProperties()
```

``` csharp
public ReadOnlyCollection<ProductProperty> GetProperties()
```

``` c++
public:
ReadOnlyCollection<ProductProperty^>^ GetProperties()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A list of product properties.  

## Remarks

Please see the remarks of the EnumerateProperties(long, string) function below for more details.

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetProperties Overload](product-getproperties-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

