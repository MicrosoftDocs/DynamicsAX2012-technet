---
title: IPeripheralsV1.Scanner Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Scanner Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.Scanner
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.scanner(v=AX.60)
ms:contentKeyID: 47344004
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.Scanner
dev_langs:
- CSharp
- C++
- VB
---

# Scanner Property

Returns the Scanner peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Scanner As IScanner
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As IScanner

value = instance.Scanner
```

``` csharp
IScanner Scanner { get; }
```

``` c++
property IScanner^ Scanner {
    IScanner^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScanner](iscanner-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [IScanner](iscanner-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

