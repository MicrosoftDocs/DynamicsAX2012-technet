---
title: ICompositionLoader.GetCacheProvider Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetCacheProvider Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetCacheProvider(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icompositionloader.getcacheprovider(v=AX.60)
ms:contentKeyID: 65319765
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetCacheProvider
dev_langs:
- CSharp
- C++
- VB
---

# GetCacheProvider Method

Gets the cache provider given the name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetCacheProvider ( _
    cacheProviderName As String _
) As IKeyedDataStoreAccessor
'Usage
Dim instance As ICompositionLoader
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
Returns the instance of cache provider.  

## See Also

#### Reference

[ICompositionLoader Interface](icompositionloader-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

