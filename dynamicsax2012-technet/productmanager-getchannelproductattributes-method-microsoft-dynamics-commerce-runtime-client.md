---
title: ProductManager.GetChannelProductAttributes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelProductAttributes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetChannelProductAttributes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getchannelproductattributes(v=AX.60)
ms:contentKeyID: 65321594
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetChannelProductAttributes
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelProductAttributes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelProductAttributes ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of AttributeProduct)
'Usage
Dim instance As ProductManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of AttributeProduct)

returnValue = instance.GetChannelProductAttributes(settings)
```

``` csharp
public ReadOnlyCollection<AttributeProduct> GetChannelProductAttributes(
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<AttributeProduct^>^ GetChannelProductAttributes(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

