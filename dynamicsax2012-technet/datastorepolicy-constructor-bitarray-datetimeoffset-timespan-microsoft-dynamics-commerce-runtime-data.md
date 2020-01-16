---
title: DataStorePolicy Constructor (BitArray, DateTimeOffset, TimeSpan) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStorePolicy Constructor (BitArray, DateTimeOffset, TimeSpan)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.#ctor(System.Collections.BitArray,System.DateTimeOffset,System.TimeSpan)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastorepolicy.datastorepolicy(v=AX.60)
ms:contentKeyID: 62209283
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DataStorePolicy Constructor (BitArray, DateTimeOffset, TimeSpan)

Initializes a new instance of the [DataStorePolicy](datastorepolicy-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    policyBits As BitArray, _
    defaultAbsoluteExpiration As DateTimeOffset, _
    defaultSlidingExpiration As TimeSpan _
)
'Usage
Dim policyBits As BitArray
Dim defaultAbsoluteExpiration As DateTimeOffset
Dim defaultSlidingExpiration As TimeSpan

Dim instance As New DataStorePolicy(policyBits, _
    defaultAbsoluteExpiration, defaultSlidingExpiration)
```

``` csharp
public DataStorePolicy(
    BitArray policyBits,
    DateTimeOffset defaultAbsoluteExpiration,
    TimeSpan defaultSlidingExpiration
)
```

``` c++
public:
DataStorePolicy(
    BitArray^ policyBits, 
    DateTimeOffset defaultAbsoluteExpiration, 
    TimeSpan defaultSlidingExpiration
)
```

#### Parameters

  - policyBits  
    Type: [System.Collections.BitArray](https://technet.microsoft.com/library/x3we7ff2\(v=ax.60\))  

<!-- end list -->

  - defaultAbsoluteExpiration  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - defaultSlidingExpiration  
    Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  

## See Also

#### Reference

[DataStorePolicy Class](datastorepolicy-class-microsoft-dynamics-commerce-runtime-data.md)

[DataStorePolicy Overload](datastorepolicy-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

