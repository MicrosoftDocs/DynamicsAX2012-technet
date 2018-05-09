---
title: ISignatureCaptureV1.CaptureCompleteEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CaptureCompleteEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.CaptureCompleteEvent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.isignaturecapturev1.capturecompleteevent(v=AX.60)
ms:contentKeyID: 49853997
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.CaptureCompleteEvent
dev_langs:
- CSharp
- C++
- VB
---

# CaptureCompleteEvent Event

Signature capture complete event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event CaptureCompleteEvent As SignatureCaptureCompleteEventHandler
'Usage
Dim instance As ISignatureCaptureV1
Dim handler As SignatureCaptureCompleteEventHandler

AddHandler instance.CaptureCompleteEvent, handler
```

``` csharp
event SignatureCaptureCompleteEventHandler CaptureCompleteEvent
```

``` c++
 event SignatureCaptureCompleteEventHandler^ CaptureCompleteEvent {
    void add (SignatureCaptureCompleteEventHandler^ value);
    void remove (SignatureCaptureCompleteEventHandler^ value);
}
```

## See Also

#### Reference

[ISignatureCaptureV1 Interface](isignaturecapturev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

