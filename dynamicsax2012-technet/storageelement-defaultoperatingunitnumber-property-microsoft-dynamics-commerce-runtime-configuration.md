---
title: StorageElement.DefaultOperatingUnitNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: DefaultOperatingUnitNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.StorageElement.DefaultOperatingUnitNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.storageelement.defaultoperatingunitnumber(v=AX.60)
ms:contentKeyID: 62207987
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.StorageElement.DefaultOperatingUnitNumber
dev_langs:
- CSharp
- C++
- VB
---

# DefaultOperatingUnitNumber Property

Gets the default operating unit for the [StorageResolver](storageresolver-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("defaultOperatingUnitNumber")> _
Public ReadOnly Property DefaultOperatingUnitNumber As String
    Get
'Usage
Dim instance As StorageElement
Dim value As String

value = instance.DefaultOperatingUnitNumber
```

``` csharp
[ConfigurationPropertyAttribute("defaultOperatingUnitNumber")]
public string DefaultOperatingUnitNumber { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"defaultOperatingUnitNumber")]
public:
virtual property String^ DefaultOperatingUnitNumber {
    String^ get () sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

#### Implements

[IStorageElement.DefaultOperatingUnitNumber](istorageelement-defaultoperatingunitnumber-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## Remarks

The operating unit used during storage resolution when no channel has been specified as part of the context. This should only be used during bootstrapping scenarios where the target channel is not yet available.

## See Also

#### Reference

[StorageElement Class](storageelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

