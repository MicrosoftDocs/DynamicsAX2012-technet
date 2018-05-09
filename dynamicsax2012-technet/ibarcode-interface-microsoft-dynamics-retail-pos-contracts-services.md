---
title: IBarcode Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IBarcode Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBarcode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ibarcode(v=AX.60)
ms:contentKeyID: 47343876
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBarcode
dev_langs:
- CSharp
- C++
- VB
---

# IBarcode Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBarcode interface performs barcode service processes scanned barcode to populate the various barcode properties.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("C6C76260-19EA-41BF-AB3C-423E8F583B56")> _
Public Interface IBarcode _
    Inherits IService, IBarcodeV1
'Usage
Dim instance As IBarcode
```

``` csharp
[GuidAttribute("C6C76260-19EA-41BF-AB3C-423E8F583B56")]
public interface IBarcode : IService, 
    IBarcodeV1
```

``` c++
[GuidAttribute(L"C6C76260-19EA-41BF-AB3C-423E8F583B56")]
public interface class IBarcode : IService, 
    IBarcodeV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

