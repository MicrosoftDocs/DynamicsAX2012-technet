---
title: IChannelPublisher.OnValidateProductAttributes Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: OnValidateProductAttributes Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.IChannelPublisher.OnValidateProductAttributes(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.ichannelpublisher.onvalidateproductattributes(v=AX.60)
ms:contentKeyID: 65317777
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.IChannelPublisher.OnValidateProductAttributes
dev_langs:
- CSharp
- C++
- VB
---

# OnValidateProductAttributes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Sub OnValidateProductAttributes ( _
    attributes As IEnumerable(Of AttributeProduct) _
)
'Usage
Dim instance As IChannelPublisher
Dim attributes As IEnumerable(Of AttributeProduct)

instance.OnValidateProductAttributes(attributes)
```

``` csharp
void OnValidateProductAttributes(
    IEnumerable<AttributeProduct> attributes
)
```

``` c++
void OnValidateProductAttributes(
    IEnumerable<AttributeProduct^>^ attributes
)
```

#### Parameters

  - attributes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<AttributeProduct\>  

## See Also

#### Reference

[IChannelPublisher Interface](ichannelpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

