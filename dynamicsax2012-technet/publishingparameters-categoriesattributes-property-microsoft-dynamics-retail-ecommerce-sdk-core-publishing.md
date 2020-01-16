---
title: PublishingParameters.CategoriesAttributes Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: CategoriesAttributes Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters.CategoriesAttributes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.publishingparameters.categoriesattributes(v=AX.60)
ms:contentKeyID: 65316379
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters.CategoriesAttributes
dev_langs:
- CSharp
- C++
- VB
---

# CategoriesAttributes Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Property CategoriesAttributes As Dictionary(Of Long, IEnumerable(Of AttributeCategory))
    Get
    Friend Set
'Usage
Dim instance As PublishingParameters
Dim value As Dictionary(Of Long, IEnumerable(Of AttributeCategory))

value = instance.CategoriesAttributes
```

``` csharp
public Dictionary<long, IEnumerable<AttributeCategory>> CategoriesAttributes { get; internal set; }
```

``` c++
public:
property Dictionary<long long, IEnumerable<AttributeCategory^>^>^ CategoriesAttributes {
    Dictionary<long long, IEnumerable<AttributeCategory^>^>^ get ();
    internal: void set (Dictionary<long long, IEnumerable<AttributeCategory^>^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<AttributeCategory\>\>  

## See Also

#### Reference

[PublishingParameters Class](publishingparameters-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

