---
title: TrackingConfig.AdapterConfig Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AdapterConfig Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingConfig.AdapterConfig
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackingconfig.adapterconfig(v=AX.60)
ms:contentKeyID: 49832982
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingConfig.AdapterConfig
dev_langs:
- CSharp
- C++
- VB
---

# AdapterConfig Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the adapter configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property AdapterConfig As ParameterSet
    Get
    Private Set
'Usage
Dim instance As TrackingConfig
Dim value As ParameterSet

value = instance.AdapterConfig
```

``` csharp
public ParameterSet AdapterConfig { get; private set; }
```

``` c++
public:
property ParameterSet^ AdapterConfig {
    ParameterSet^ get ();
    private: void set (ParameterSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[TrackingConfig Class](trackingconfig-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

