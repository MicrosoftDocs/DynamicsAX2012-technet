---
title: IPeripheralsV2.SignatureCapture Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SignatureCapture Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV2.SignatureCapture
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv2.signaturecapture(v=AX.60)
ms:contentKeyID: 49855904
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV2.SignatureCapture
dev_langs:
- CSharp
- C++
- VB
---

# SignatureCapture Property

Signature capture peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SignatureCapture As ISignatureCapture
    Get
'Usage
Dim instance As IPeripheralsV2
Dim value As ISignatureCapture

value = instance.SignatureCapture
```

``` csharp
ISignatureCapture SignatureCapture { get; }
```

``` c++
property ISignatureCapture^ SignatureCapture {
    ISignatureCapture^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCapture](isignaturecapture-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ISignatureCapture](isignaturecapture-interface-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IPeripheralsV2 Interface](iperipheralsv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

