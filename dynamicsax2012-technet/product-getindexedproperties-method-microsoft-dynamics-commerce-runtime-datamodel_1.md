---
title: Product.GetIndexedProperties Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetIndexedProperties Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetIndexedProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.getindexedproperties(v=AX.60)
ms:contentKeyID: 62212561
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetIndexedProperties Method

Enumerates the product's attributes, together with their default values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetIndexedProperties As ProductPropertyDictionary
'Usage
Dim instance As Product
Dim returnValue As ProductPropertyDictionary

returnValue = instance.GetIndexedProperties()
```

``` csharp
public ProductPropertyDictionary GetIndexedProperties()
```

``` c++
public:
ProductPropertyDictionary^ GetIndexedProperties()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A collection of product properties, indexed on the property key name.  

## Remarks

Please see the remarks of the EnumerateProperties(long, string) function below for more details.

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetIndexedProperties Overload](product-getindexedproperties-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

