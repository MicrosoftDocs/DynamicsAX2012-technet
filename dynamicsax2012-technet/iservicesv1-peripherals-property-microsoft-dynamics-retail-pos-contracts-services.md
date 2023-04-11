---
title: IServicesV1.Peripherals Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Peripherals Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.Peripherals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv1.peripherals(v=AX.60)
ms:contentKeyID: 47343875
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.Peripherals
dev_langs:
- CSharp
- C++
- VB
---

# Peripherals Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Peripherals service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Peripherals As IPeripherals
    Get
    Set
'Usage
Dim instance As IServicesV1
Dim value As IPeripherals

value = instance.Peripherals

instance.Peripherals = value
```

``` csharp
IPeripherals Peripherals { get; set; }
```

``` c++
property IPeripherals^ Peripherals {
    IPeripherals^ get ();
    void set (IPeripherals^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripherals](iperipherals-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [IPeripherals](iperipherals-interface-microsoft-dynamics-retail-pos-contracts-services.md) .  

## See Also

#### Reference

[IServicesV1 Interface](iservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

