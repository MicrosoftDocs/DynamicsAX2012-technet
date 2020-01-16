---
title: IPeripheralsV1.Printer Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Printer Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.Printer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.printer(v=AX.60)
ms:contentKeyID: 47344283
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.Printer
dev_langs:
- CSharp
- C++
- VB
---

# Printer Property

Returns the printer peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Printer As IPrinter
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As IPrinter

value = instance.Printer
```

``` csharp
IPrinter Printer { get; }
```

``` c++
property IPrinter^ Printer {
    IPrinter^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinter](iprinter-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [IPrinter](iprinter-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

