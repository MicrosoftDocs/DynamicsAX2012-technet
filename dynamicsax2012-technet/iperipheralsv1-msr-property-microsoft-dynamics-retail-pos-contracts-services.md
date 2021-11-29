---
title: IPeripheralsV1.MSR Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: MSR Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.MSR
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.msr(v=AX.60)
ms:contentKeyID: 47344190
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.MSR
dev_langs:
- CSharp
- C++
- VB
---

# MSR Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the MSR peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property MSR As IMSR
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As IMSR

value = instance.MSR
```

``` csharp
IMSR MSR { get; }
```

``` c++
property IMSR^ MSR {
    IMSR^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSR](imsr-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [IMSR](imsr-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

