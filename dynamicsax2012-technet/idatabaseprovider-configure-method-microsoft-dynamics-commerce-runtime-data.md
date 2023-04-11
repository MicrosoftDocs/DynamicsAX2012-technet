---
title: IDatabaseProvider.Configure Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Configure Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.Configure(System.Collections.Generic.IDictionary{System.String,System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseprovider.configure(v=AX.60)
ms:contentKeyID: 65323139
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseProvider.Configure
dev_langs:
- CSharp
- C++
- VB
---

# Configure Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Configures the database provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Sub Configure ( _
    configurationDictionary As IDictionary(Of String, String) _
)
'Usage
Dim instance As IDatabaseProvider
Dim configurationDictionary As IDictionary(Of String, String)

instance.Configure(configurationDictionary)
```

``` csharp
void Configure(
    IDictionary<string, string> configurationDictionary
)
```

``` c++
void Configure(
    IDictionary<String^, String^>^ configurationDictionary
)
```

#### Parameters

  - configurationDictionary  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[IDatabaseProvider Interface](idatabaseprovider-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

