---
title: IPeripheralsV1.KeyLock Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: KeyLock Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.KeyLock
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.keylock(v=AX.60)
ms:contentKeyID: 47344292
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.KeyLock
dev_langs:
- CSharp
- C++
- VB
---

# KeyLock Property

Returns the KeyLock peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property KeyLock As IKeyLock
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As IKeyLock

value = instance.KeyLock
```

``` csharp
IKeyLock KeyLock { get; }
```

``` c++
property IKeyLock^ KeyLock {
    IKeyLock^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IKeyLock](ikeylock-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [IKeyLock](ikeylock-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

