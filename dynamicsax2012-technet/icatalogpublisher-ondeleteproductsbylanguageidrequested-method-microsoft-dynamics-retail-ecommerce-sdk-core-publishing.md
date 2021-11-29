---
title: ICatalogPublisher.OnDeleteProductsByLanguageIdRequested Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: OnDeleteProductsByLanguageIdRequested Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnDeleteProductsByLanguageIdRequested(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.icatalogpublisher.ondeleteproductsbylanguageidrequested(v=AX.60)
ms:contentKeyID: 65315873
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnDeleteProductsByLanguageIdRequested
dev_langs:
- CSharp
- C++
- VB
---

# OnDeleteProductsByLanguageIdRequested Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Sub OnDeleteProductsByLanguageIdRequested ( _
    languageIds As Dictionary(Of String, List(Of String)) _
)
'Usage
Dim instance As ICatalogPublisher
Dim languageIds As Dictionary(Of String, List(Of String))

instance.OnDeleteProductsByLanguageIdRequested(languageIds)
```

``` csharp
void OnDeleteProductsByLanguageIdRequested(
    Dictionary<string, List<string>> languageIds
)
```

``` c++
void OnDeleteProductsByLanguageIdRequested(
    Dictionary<String^, List<String^>^>^ languageIds
)
```

#### Parameters

  - languageIds  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>\>  

## See Also

#### Reference

[ICatalogPublisher Interface](icatalogpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

