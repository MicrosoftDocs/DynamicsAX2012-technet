---
title: SignatureCaptureCompleteEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SignatureCaptureCompleteEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.SignatureCaptureCompleteEventHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.signaturecapturecompleteeventhandler(v=AX.60)
ms:contentKeyID: 49844567
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.SignatureCaptureCompleteEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# SignatureCaptureCompleteEventHandler Delegate

Signature capture device entry complete event handler.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub SignatureCaptureCompleteEventHandler ( _
    sender As Object, _
    eventArgs As ISignatureCaptureInfo _
)
'Usage
Dim instance As New SignatureCaptureCompleteEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void SignatureCaptureCompleteEventHandler(
    Object sender,
    ISignatureCaptureInfo eventArgs
)
```

``` c++
public delegate void SignatureCaptureCompleteEventHandler(
    Object^ sender, 
    ISignatureCaptureInfo^ eventArgs
)
```

#### Parameters

  - sender  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - eventArgs  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISignatureCaptureInfo](isignaturecaptureinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

