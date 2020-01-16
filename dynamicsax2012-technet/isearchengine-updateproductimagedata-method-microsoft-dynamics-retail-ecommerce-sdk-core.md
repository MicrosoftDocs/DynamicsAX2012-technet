---
title: ISearchEngine.UpdateProductImageData Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core)
TOCTitle: UpdateProductImageData Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.UpdateProductImageData(Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.isearchengine.updateproductimagedata(v=AX.60)
ms:contentKeyID: 65316299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.UpdateProductImageData
dev_langs:
- CSharp
- C++
- VB
---

# UpdateProductImageData Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Function UpdateProductImageData ( _
    imageSearchValue As RichMediaLocations _
) As ImageInfo
'Usage
Dim instance As ISearchEngine
Dim imageSearchValue As RichMediaLocations
Dim returnValue As ImageInfo

returnValue = instance.UpdateProductImageData(imageSearchValue)
```

``` csharp
ImageInfo UpdateProductImageData(
    RichMediaLocations imageSearchValue
)
```

``` c++
ImageInfo^ UpdateProductImageData(
    RichMediaLocations^ imageSearchValue
)
```

#### Parameters

  - imageSearchValue  
    Type: RichMediaLocations  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ImageInfo](imageinfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[ISearchEngine Interface](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)

