---
title: PublishingParameters.Categories Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: Categories Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters.Categories
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.publishingparameters.categories(v=AX.60)
ms:contentKeyID: 65318563
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters.Categories
dev_langs:
- CSharp
- C++
- VB
---

# Categories Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Property Categories As IEnumerable(Of Category)
    Get
    Friend Set
'Usage
Dim instance As PublishingParameters
Dim value As IEnumerable(Of Category)

value = instance.Categories
```

``` csharp
public IEnumerable<Category> Categories { get; internal set; }
```

``` c++
public:
property IEnumerable<Category^>^ Categories {
    IEnumerable<Category^>^ get ();
    internal: void set (IEnumerable<Category^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Category\>  

## See Also

#### Reference

[PublishingParameters Class](publishingparameters-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

