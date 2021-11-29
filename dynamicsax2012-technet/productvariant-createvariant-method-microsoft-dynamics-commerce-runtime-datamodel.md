---
title: ProductVariant.CreateVariant Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreateVariant Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.CreateVariant(System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.createvariant(v=AX.60)
ms:contentKeyID: 62213413
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.CreateVariant
dev_langs:
- CSharp
- C++
- VB
---

# CreateVariant Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new variant using the specified combination values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateVariant ( _
    colorId As String, _
    sizeId As String, _
    styleId As String, _
    configId As String _
) As ProductVariant
'Usage
Dim colorId As String
Dim sizeId As String
Dim styleId As String
Dim configId As String
Dim returnValue As ProductVariant

returnValue = ProductVariant.CreateVariant(colorId, _
    sizeId, styleId, configId)
```

``` csharp
public static ProductVariant CreateVariant(
    string colorId,
    string sizeId,
    string styleId,
    string configId
)
```

``` c++
public:
static ProductVariant^ CreateVariant(
    String^ colorId, 
    String^ sizeId, 
    String^ styleId, 
    String^ configId
)
```

#### Parameters

  - colorId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - sizeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - styleId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - configId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A newly created variant.  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

