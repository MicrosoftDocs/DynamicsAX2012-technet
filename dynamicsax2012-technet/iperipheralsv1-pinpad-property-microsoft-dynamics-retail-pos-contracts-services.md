---
title: IPeripheralsV1.PinPad Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PinPad Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.PinPad
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.pinpad(v=AX.60)
ms:contentKeyID: 47343981
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.PinPad
dev_langs:
- CSharp
- C++
- VB
---

# PinPad Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the PinPad peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property PinPad As IPinPad
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As IPinPad

value = instance.PinPad
```

``` csharp
IPinPad PinPad { get; }
```

``` c++
property IPinPad^ PinPad {
    IPinPad^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPinPad](ipinpad-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [IPinPad](ipinpad-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

