---
title: IPeripheralsV1.RFIDScanner Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RFIDScanner Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.RFIDScanner
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv1.rfidscanner(v=AX.60)
ms:contentKeyID: 47344230
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV1.RFIDScanner
dev_langs:
- CSharp
- C++
- VB
---

# RFIDScanner Property

Returns the RFIDScanner peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property RFIDScanner As IRadioFrequencyIDScanner
    Get
'Usage
Dim instance As IPeripheralsV1
Dim value As IRadioFrequencyIDScanner

value = instance.RFIDScanner
```

``` csharp
IRadioFrequencyIDScanner RFIDScanner { get; }
```

``` c++
property IRadioFrequencyIDScanner^ RFIDScanner {
    IRadioFrequencyIDScanner^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRadioFrequencyIDScanner](iradiofrequencyidscanner-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
The [IRadioFrequencyIDScanner](iradiofrequencyidscanner-interface-microsoft-dynamics-retail-pos-contracts-services.md) peripheral device.  

## See Also

#### Reference

[IPeripheralsV1 Interface](iperipheralsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

