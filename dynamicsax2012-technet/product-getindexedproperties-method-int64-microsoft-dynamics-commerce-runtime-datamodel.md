---
title: Product.GetIndexedProperties Method (Int64) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetIndexedProperties Method (Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetIndexedProperties(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.getindexedproperties(v=AX.60)
ms:contentKeyID: 62215212
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetIndexedProperties Method (Int64)

Given a variant id, returns the properties of that variant, as a collection indexed on the property key name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetIndexedProperties ( _
    variantId As Long _
) As ProductPropertyDictionary
'Usage
Dim instance As Product
Dim variantId As Long
Dim returnValue As ProductPropertyDictionary

returnValue = instance.GetIndexedProperties(variantId)
```

``` csharp
public ProductPropertyDictionary GetIndexedProperties(
    long variantId
)
```

``` c++
public:
ProductPropertyDictionary^ GetIndexedProperties(
    long long variantId
)
```

#### Parameters

  - variantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The default translation of the variant's properties.  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetIndexedProperties Overload](product-getindexedproperties-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

