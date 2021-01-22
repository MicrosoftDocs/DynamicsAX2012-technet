---
title: CacheAttribute.CacheProviderName Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CacheProviderName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CacheAttribute.CacheProviderName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.cacheattribute.cacheprovidername(v=AX.60)
ms:contentKeyID: 65318124
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CacheAttribute.CacheProviderName
dev_langs:
- CSharp
- C++
- VB
---

# CacheProviderName Property

Gets or sets the name of the cache provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property CacheProviderName As String
    Get
    Set
'Usage
Dim instance As CacheAttribute
Dim value As String

value = instance.CacheProviderName

instance.CacheProviderName = value
```

``` csharp
public string CacheProviderName { get; set; }
```

``` c++
public:
property String^ CacheProviderName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CacheAttribute Class](cacheattribute-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

