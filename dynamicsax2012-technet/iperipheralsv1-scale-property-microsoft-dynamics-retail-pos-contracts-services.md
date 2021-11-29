---
title: IPeripheralsV1.Scale Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Scale Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.Scale
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.scale(v=AX.60)
ms:contentKeyID: 47344389
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.Scale
dev_langs:
- CSharp
- C++
- VB
---

# Scale Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the Scale peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Scale As IScale
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As IScale

value = instance.Scale
```

``` csharp
IScale Scale { get; }
```

``` c++
property IScale^ Scale {
    IScale^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScale](iscale-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [IScale](iscale-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

