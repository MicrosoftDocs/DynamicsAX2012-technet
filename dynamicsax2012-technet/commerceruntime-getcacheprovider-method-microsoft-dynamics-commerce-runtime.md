---
title: CommerceRuntime.GetCacheProvider Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetCacheProvider Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.GetCacheProvider(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.getcacheprovider(v=AX.60)
ms:contentKeyID: 65318485
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.GetCacheProvider
dev_langs:
- CSharp
- C++
- VB
---

# GetCacheProvider Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Function GetCacheProvider ( _
    cacheProviderName As String _
) As IKeyedDataStoreAccessor
'Usage
Dim instance As CommerceRuntime
Dim cacheProviderName As String
Dim returnValue As IKeyedDataStoreAccessor

returnValue = instance.GetCacheProvider(cacheProviderName)
```

``` csharp
public IKeyedDataStoreAccessor GetCacheProvider(
    string cacheProviderName
)
```

``` c++
public:
virtual IKeyedDataStoreAccessor^ GetCacheProvider(
    String^ cacheProviderName
) sealed
```

#### Parameters

  - cacheProviderName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[ICommerceRuntime.GetCacheProvider(String)](icommerceruntime-getcacheprovider-method-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

