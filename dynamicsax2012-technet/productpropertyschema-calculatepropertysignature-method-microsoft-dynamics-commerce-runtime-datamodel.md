---
title: ProductPropertySchema.CalculatePropertySignature Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CalculatePropertySignature Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertySchema.CalculatePropertySignature(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertyschema.calculatepropertysignature(v=AX.60)
ms:contentKeyID: 65320782
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertySchema.CalculatePropertySignature
dev_langs:
- CSharp
- C++
- VB
---

# CalculatePropertySignature Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function CalculatePropertySignature ( _
    propertySet As ProductPropertyDictionary _
) As BitArray
'Usage
Dim instance As ProductPropertySchema
Dim propertySet As ProductPropertyDictionary
Dim returnValue As BitArray

returnValue = instance.CalculatePropertySignature(propertySet)
```

``` csharp
public BitArray CalculatePropertySignature(
    ProductPropertyDictionary propertySet
)
```

``` c++
public:
BitArray^ CalculatePropertySignature(
    ProductPropertyDictionary^ propertySet
)
```

#### Parameters

  - propertySet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.BitArray](https://technet.microsoft.com/library/x3we7ff2\(v=ax.60\))  

## See Also

#### Reference

[ProductPropertySchema Class](productpropertyschema-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

