---
title: IServicesV1.Barcode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Barcode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.Barcode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv1.barcode(v=AX.60)
ms:contentKeyID: 47344094
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.Barcode
dev_langs:
- CSharp
- C++
- VB
---

# Barcode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Barcode service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Barcode As IBarcode
    Get
'Usage
Dim instance As IServicesV1
Dim value As IBarcode

value = instance.Barcode
```

``` csharp
IBarcode Barcode { get; }
```

``` c++
property IBarcode^ Barcode {
    IBarcode^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBarcode](ibarcode-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [IBarcode](ibarcode-interface-microsoft-dynamics-retail-pos-contracts-services.md) .  

## See Also

#### Reference

[IServicesV1 Interface](iservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

