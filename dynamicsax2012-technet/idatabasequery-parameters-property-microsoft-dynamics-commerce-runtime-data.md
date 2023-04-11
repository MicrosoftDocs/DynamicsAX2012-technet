---
title: IDatabaseQuery.Parameters Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Parameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery.Parameters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabasequery.parameters(v=AX.60)
ms:contentKeyID: 65322785
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery.Parameters
dev_langs:
- CSharp
- C++
- VB
---

# Parameters Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a dictionary of parameters associated to this command.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Parameters As IDictionary(Of String, Object)
    Get
'Usage
Dim instance As IDatabaseQuery
Dim value As IDictionary(Of String, Object)

value = instance.Parameters
```

``` csharp
IDictionary<string, Object> Parameters { get; }
```

``` c++
property IDictionary<String^, Object^>^ Parameters {
    IDictionary<String^, Object^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[IDatabaseQuery Interface](idatabasequery-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

