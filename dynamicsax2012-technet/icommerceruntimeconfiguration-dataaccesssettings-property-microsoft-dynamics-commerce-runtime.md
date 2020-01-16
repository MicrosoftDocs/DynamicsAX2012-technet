---
title: ICommerceRuntimeConfiguration.DataAccessSettings Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DataAccessSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.DataAccessSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntimeconfiguration.dataaccesssettings(v=AX.60)
ms:contentKeyID: 65320047
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.DataAccessSettings
dev_langs:
- CSharp
- C++
- VB
---

# DataAccessSettings Property

Gets the data access element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property DataAccessSettings As IDictionary(Of String, String)
    Get
'Usage
Dim instance As ICommerceRuntimeConfiguration
Dim value As IDictionary(Of String, String)

value = instance.DataAccessSettings
```

``` csharp
IDictionary<string, string> DataAccessSettings { get; }
```

``` c++
property IDictionary<String^, String^>^ DataAccessSettings {
    IDictionary<String^, String^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[ICommerceRuntimeConfiguration Interface](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

