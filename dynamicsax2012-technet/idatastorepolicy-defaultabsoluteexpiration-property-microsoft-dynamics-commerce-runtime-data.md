---
title: IDataStorePolicy.DefaultAbsoluteExpiration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DefaultAbsoluteExpiration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDataStorePolicy.DefaultAbsoluteExpiration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatastorepolicy.defaultabsoluteexpiration(v=AX.60)
ms:contentKeyID: 65318426
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDataStorePolicy.DefaultAbsoluteExpiration
dev_langs:
- CSharp
- C++
- VB
---

# DefaultAbsoluteExpiration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the default absolute expiration for this data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Property DefaultAbsoluteExpiration As DateTimeOffset
    Get
    Set
'Usage
Dim instance As IDataStorePolicy
Dim value As DateTimeOffset

value = instance.DefaultAbsoluteExpiration

instance.DefaultAbsoluteExpiration = value
```

``` csharp
DateTimeOffset DefaultAbsoluteExpiration { get; set; }
```

``` c++
property DateTimeOffset DefaultAbsoluteExpiration {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[IDataStorePolicy Interface](idatastorepolicy-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

