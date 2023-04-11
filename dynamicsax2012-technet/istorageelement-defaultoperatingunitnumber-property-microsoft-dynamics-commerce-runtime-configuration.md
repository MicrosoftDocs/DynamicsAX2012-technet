---
title: IStorageElement.DefaultOperatingUnitNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: DefaultOperatingUnitNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.IStorageElement.DefaultOperatingUnitNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.istorageelement.defaultoperatingunitnumber(v=AX.60)
ms:contentKeyID: 65321329
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.IStorageElement.DefaultOperatingUnitNumber
dev_langs:
- CSharp
- C++
- VB
---

# DefaultOperatingUnitNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default operating unit for the StorageResolver class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property DefaultOperatingUnitNumber As String
    Get
'Usage
Dim instance As IStorageElement
Dim value As String

value = instance.DefaultOperatingUnitNumber
```

``` csharp
string DefaultOperatingUnitNumber { get; }
```

``` c++
property String^ DefaultOperatingUnitNumber {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

The operating unit used during storage resolution when no channel has been specified as part of the context. This should only be used during bootstrapping scenarios where the target channel is not yet available.

## See Also

#### Reference

[IStorageElement Interface](istorageelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

