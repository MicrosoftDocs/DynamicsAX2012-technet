---
title: ICompositionElement.Source Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Source Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICompositionElement.Source
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.icompositionelement.source(v=AX.60)
ms:contentKeyID: 65317757
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICompositionElement.Source
dev_langs:
- CSharp
- C++
- VB
---

# Source Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the load source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Source As String
    Get
'Usage
Dim instance As ICompositionElement
Dim value As String

value = instance.Source
```

``` csharp
string Source { get; }
```

``` c++
property String^ Source {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Supported values include type, assembly or directory.

## See Also

#### Reference

[ICompositionElement Interface](icompositionelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

