---
title: IServicesV2.TimeRegistration Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TimeRegistration Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV2.TimeRegistration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv2.timeregistration(v=AX.60)
ms:contentKeyID: 49850697
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV2.TimeRegistration
dev_langs:
- CSharp
- C++
- VB
---

# TimeRegistration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Time clock service.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TimeRegistration As ITimeRegistration
    Get
'Usage
Dim instance As IServicesV2
Dim value As ITimeRegistration

value = instance.TimeRegistration
```

``` csharp
ITimeRegistration TimeRegistration { get; }
```

``` c++
property ITimeRegistration^ TimeRegistration {
    ITimeRegistration^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITimeRegistration](itimeregistration-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ITimeRegistration](itimeregistration-interface-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IServicesV2 Interface](iservicesv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

