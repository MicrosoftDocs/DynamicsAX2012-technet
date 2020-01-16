---
title: ICommerceRuntime.GetCacheProvider Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetCacheProvider Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.GetCacheProvider(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntime.getcacheprovider(v=AX.60)
ms:contentKeyID: 65320815
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.GetCacheProvider
dev_langs:
- CSharp
- C++
- VB
---

# GetCacheProvider Method

Gets the cache accessor by provider name declared in cache metadata attribute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetCacheProvider ( _
    cacheProviderName As String _
) As IKeyedDataStoreAccessor
'Usage
Dim instance As ICommerceRuntime
Dim cacheProviderName As String
Dim returnValue As IKeyedDataStoreAccessor

returnValue = instance.GetCacheProvider(cacheProviderName)
```

``` csharp
IKeyedDataStoreAccessor GetCacheProvider(
    string cacheProviderName
)
```

``` c++
IKeyedDataStoreAccessor^ GetCacheProvider(
    String^ cacheProviderName
)
```

#### Parameters

  - cacheProviderName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md)  
The instance of the cache provider.  

## See Also

#### Reference

[ICommerceRuntime Interface](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

