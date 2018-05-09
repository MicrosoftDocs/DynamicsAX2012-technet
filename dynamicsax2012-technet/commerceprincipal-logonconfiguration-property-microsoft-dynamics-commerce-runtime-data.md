---
title: CommercePrincipal.LogOnConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: LogOnConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.LogOnConfiguration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.logonconfiguration(v=AX.60)
ms:contentKeyID: 62207268
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.LogOnConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# LogOnConfiguration Property

Gets the Logon configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property LogOnConfiguration As LogOnConfiguration
    Get
'Usage
Dim instance As CommercePrincipal
Dim value As LogOnConfiguration

value = instance.LogOnConfiguration
```

``` csharp
[DataMemberAttribute]
public LogOnConfiguration LogOnConfiguration { get; }
```

``` c++
[DataMemberAttribute]
public:
property LogOnConfiguration LogOnConfiguration {
    LogOnConfiguration get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

