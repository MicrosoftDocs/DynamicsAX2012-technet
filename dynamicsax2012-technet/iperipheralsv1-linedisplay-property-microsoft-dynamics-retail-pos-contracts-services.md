---
title: IPeripheralsV1.LineDisplay Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: LineDisplay Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.LineDisplay
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.linedisplay(v=AX.60)
ms:contentKeyID: 47344173
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.LineDisplay
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplay Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the LineDisplay peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property LineDisplay As ILineDisplay
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As ILineDisplay

value = instance.LineDisplay
```

``` csharp
ILineDisplay LineDisplay { get; }
```

``` c++
property ILineDisplay^ LineDisplay {
    ILineDisplay^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILineDisplay](ilinedisplay-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [ILineDisplay](ilinedisplay-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

