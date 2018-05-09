---
title: ICatalogPublisher.OnDeleteProductsByCatalogIdRequested Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: OnDeleteProductsByCatalogIdRequested Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnDeleteProductsByCatalogIdRequested(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.Int64}})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.icatalogpublisher.ondeleteproductsbycatalogidrequested(v=AX.60)
ms:contentKeyID: 65318016
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnDeleteProductsByCatalogIdRequested
dev_langs:
- CSharp
- C++
- VB
---

# OnDeleteProductsByCatalogIdRequested Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Sub OnDeleteProductsByCatalogIdRequested ( _
    catalogs As Dictionary(Of String, List(Of Long)) _
)
'Usage
Dim instance As ICatalogPublisher
Dim catalogs As Dictionary(Of String, List(Of Long))

instance.OnDeleteProductsByCatalogIdRequested(catalogs)
```

``` csharp
void OnDeleteProductsByCatalogIdRequested(
    Dictionary<string, List<long>> catalogs
)
```

``` c++
void OnDeleteProductsByCatalogIdRequested(
    Dictionary<String^, List<long long>^>^ catalogs
)
```

#### Parameters

  - catalogs  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [List](https://technet.microsoft.com/en-us/library/6sh2ey19\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>\>  

## See Also

#### Reference

[ICatalogPublisher Interface](icatalogpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

