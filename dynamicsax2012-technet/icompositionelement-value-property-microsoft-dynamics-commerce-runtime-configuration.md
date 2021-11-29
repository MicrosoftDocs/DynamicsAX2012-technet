---
title: ICompositionElement.Value Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICompositionElement.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.icompositionelement.value(v=AX.60)
ms:contentKeyID: 65317141
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICompositionElement.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value for the load source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Value As String
    Get
'Usage
Dim instance As ICompositionElement
Dim value As String

value = instance.Value
```

``` csharp
string Value { get; }
```

``` c++
property String^ Value {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICompositionElement Interface](icompositionelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

