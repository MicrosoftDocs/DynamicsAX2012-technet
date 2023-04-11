---
title: DataStorePolicy.DefaultSlidingExpiration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DefaultSlidingExpiration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.DefaultSlidingExpiration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastorepolicy.defaultslidingexpiration(v=AX.60)
ms:contentKeyID: 62214507
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.DefaultSlidingExpiration
dev_langs:
- CSharp
- C++
- VB
---

# DefaultSlidingExpiration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default sliding expiration for this data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property DefaultSlidingExpiration As TimeSpan
    Get
    Set
'Usage
Dim instance As DataStorePolicy
Dim value As TimeSpan

value = instance.DefaultSlidingExpiration

instance.DefaultSlidingExpiration = value
```

``` csharp
public TimeSpan DefaultSlidingExpiration { get; set; }
```

``` c++
public:
virtual property TimeSpan DefaultSlidingExpiration {
    TimeSpan get () sealed;
    void set (TimeSpan value) sealed;
}
```

#### Property Value

Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  
Returns [TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\)).  

#### Implements

[IDataStorePolicy.DefaultSlidingExpiration](idatastorepolicy-defaultslidingexpiration-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStorePolicy Class](datastorepolicy-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

