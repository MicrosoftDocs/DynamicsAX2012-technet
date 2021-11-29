---
title: KitMapper.GetKitComponentImageData Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers)
TOCTitle: GetKitComponentImageData Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers.KitMapper.GetKitComponentImageData(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.Product,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.mappers.kitmapper.getkitcomponentimagedata(v=AX.60)
ms:contentKeyID: 65316747
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers.KitMapper.GetKitComponentImageData
dev_langs:
- CSharp
- C++
- VB
---

# GetKitComponentImageData Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers](microsoft-dynamics-retail-ecommerce-sdk-core-mappers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetKitComponentImageData ( _
    kitComponentProductId As Long, _
    kitComponentProductMaster As Product, _
    searchEngine As ISearchEngine _
) As ImageInfo
'Usage
Dim kitComponentProductId As Long
Dim kitComponentProductMaster As Product
Dim searchEngine As ISearchEngine
Dim returnValue As ImageInfo

returnValue = Me.GetKitComponentImageData(kitComponentProductId, _
    kitComponentProductMaster, searchEngine)
```

``` csharp
protected virtual ImageInfo GetKitComponentImageData(
    long kitComponentProductId,
    Product kitComponentProductMaster,
    ISearchEngine searchEngine
)
```

``` c++
protected:
virtual ImageInfo^ GetKitComponentImageData(
    long long kitComponentProductId, 
    Product^ kitComponentProductMaster, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - kitComponentProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentProductMaster  
    Type: Product  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ImageInfo](imageinfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[KitMapper Class](kitmapper-class-microsoft-dynamics-retail-ecommerce-sdk-core-mappers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Mappers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-mappers-namespace.md)

