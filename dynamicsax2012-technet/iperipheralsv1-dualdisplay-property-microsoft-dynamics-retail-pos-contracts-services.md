---
title: IPeripheralsV1.DualDisplay Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DualDisplay Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.DualDisplay
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.dualdisplay(v=AX.60)
ms:contentKeyID: 47344313
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.DualDisplay
dev_langs:
- CSharp
- C++
- VB
---

# DualDisplay Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns a DualDisplay peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property DualDisplay As IDualDisplay
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As IDualDisplay

value = instance.DualDisplay
```

``` csharp
IDualDisplay DualDisplay { get; }
```

``` c++
property IDualDisplay^ DualDisplay {
    IDualDisplay^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDualDisplay](idualdisplay-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [IDualDisplay](idualdisplay-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

