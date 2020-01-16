---
title: DataAccessor Constructor  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: DataAccessor Constructor
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.DataAccessor.#ctor(System.Int64,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.dataaccessor.dataaccessor(v=AX.60)
ms:contentKeyID: 65318484
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.DataAccessor.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DataAccessor Constructor

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    connectionString As String, _
    maxPageSize As Integer _
)
'Usage
Dim channelId As Long
Dim connectionString As String
Dim maxPageSize As Integer

Dim instance As New DataAccessor(channelId, _
    connectionString, maxPageSize)
```

``` csharp
public DataAccessor(
    long channelId,
    string connectionString,
    int maxPageSize
)
```

``` c++
public:
DataAccessor(
    long long channelId, 
    String^ connectionString, 
    int maxPageSize
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - connectionString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maxPageSize  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[DataAccessor Class](dataaccessor-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

