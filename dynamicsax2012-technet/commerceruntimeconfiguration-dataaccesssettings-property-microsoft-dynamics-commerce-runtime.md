---
title: CommerceRuntimeConfiguration.DataAccessSettings Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DataAccessSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.DataAccessSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.dataaccesssettings(v=AX.60)
ms:contentKeyID: 65319179
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.DataAccessSettings
dev_langs:
- CSharp
- C++
- VB
---

# DataAccessSettings Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Property DataAccessSettings As IDictionary(Of String, String)
    Get
    Private Set
'Usage
Dim instance As CommerceRuntimeConfiguration
Dim value As IDictionary(Of String, String)

value = instance.DataAccessSettings
```

``` csharp
public IDictionary<string, string> DataAccessSettings { get; private set; }
```

``` c++
public:
virtual property IDictionary<String^, String^>^ DataAccessSettings {
    IDictionary<String^, String^>^ get () sealed;
    private: void set (IDictionary<String^, String^>^ value) sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Implements

[ICommerceRuntimeConfiguration.DataAccessSettings](icommerceruntimeconfiguration-dataaccesssettings-property-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

