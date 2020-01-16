---
title: IDataStorePolicy.DefaultSlidingExpiration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DefaultSlidingExpiration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDataStorePolicy.DefaultSlidingExpiration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatastorepolicy.defaultslidingexpiration(v=AX.60)
ms:contentKeyID: 65321939
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDataStorePolicy.DefaultSlidingExpiration
dev_langs:
- CSharp
- C++
- VB
---

# DefaultSlidingExpiration Property

Gets or sets the default sliding expiration for this data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Property DefaultSlidingExpiration As TimeSpan
    Get
    Set
'Usage
Dim instance As IDataStorePolicy
Dim value As TimeSpan

value = instance.DefaultSlidingExpiration

instance.DefaultSlidingExpiration = value
```

``` csharp
TimeSpan DefaultSlidingExpiration { get; set; }
```

``` c++
property TimeSpan DefaultSlidingExpiration {
    TimeSpan get ();
    void set (TimeSpan value);
}
```

#### Property Value

Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  
Returns [TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\)).  

## See Also

#### Reference

[IDataStorePolicy Interface](idatastorepolicy-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

