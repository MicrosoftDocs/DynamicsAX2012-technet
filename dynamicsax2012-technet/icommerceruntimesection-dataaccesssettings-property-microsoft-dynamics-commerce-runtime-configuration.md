---
title: ICommerceRuntimeSection.DataAccessSettings Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: DataAccessSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.DataAccessSettings
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.configuration.icommerceruntimesection.dataaccesssettings(v=AX.60)
ms:contentKeyID: 65322501
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.DataAccessSettings
dev_langs:
- CSharp
- C++
- VB
---

# DataAccessSettings Property

Gets the data access element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property DataAccessSettings As IDictionary(Of String, String)
    Get
'Usage
Dim instance As ICommerceRuntimeSection
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

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[ICommerceRuntimeSection Interface](icommerceruntimesection-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

