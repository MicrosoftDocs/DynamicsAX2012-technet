---
title: ICacheControlElement.ForceCacheLookupHits Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: ForceCacheLookupHits Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICacheControlElement.ForceCacheLookupHits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.icachecontrolelement.forcecachelookuphits(v=AX.60)
ms:contentKeyID: 65322492
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICacheControlElement.ForceCacheLookupHits
dev_langs:
- CSharp
- C++
- VB
---

# ForceCacheLookupHits Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether cache lookups should always return positive or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ForceCacheLookupHits As Boolean
    Get
'Usage
Dim instance As ICacheControlElement
Dim value As Boolean

value = instance.ForceCacheLookupHits
```

``` csharp
bool ForceCacheLookupHits { get; }
```

``` c++
property bool ForceCacheLookupHits {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ICacheControlElement Interface](icachecontrolelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

