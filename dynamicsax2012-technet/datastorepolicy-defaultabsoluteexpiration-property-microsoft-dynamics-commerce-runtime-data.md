---
title: DataStorePolicy.DefaultAbsoluteExpiration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DefaultAbsoluteExpiration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.DefaultAbsoluteExpiration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastorepolicy.defaultabsoluteexpiration(v=AX.60)
ms:contentKeyID: 62213415
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.DefaultAbsoluteExpiration
dev_langs:
- CSharp
- C++
- VB
---

# DefaultAbsoluteExpiration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default absolute expiration for this data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property DefaultAbsoluteExpiration As DateTimeOffset
    Get
    Set
'Usage
Dim instance As DataStorePolicy
Dim value As DateTimeOffset

value = instance.DefaultAbsoluteExpiration

instance.DefaultAbsoluteExpiration = value
```

``` csharp
public DateTimeOffset DefaultAbsoluteExpiration { get; set; }
```

``` c++
public:
virtual property DateTimeOffset DefaultAbsoluteExpiration {
    DateTimeOffset get () sealed;
    void set (DateTimeOffset value) sealed;
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

#### Implements

[IDataStorePolicy.DefaultAbsoluteExpiration](idatastorepolicy-defaultabsoluteexpiration-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStorePolicy Class](datastorepolicy-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

