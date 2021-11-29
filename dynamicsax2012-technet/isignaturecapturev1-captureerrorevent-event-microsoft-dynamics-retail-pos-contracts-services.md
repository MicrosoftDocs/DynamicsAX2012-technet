---
title: ISignatureCaptureV1.CaptureErrorEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CaptureErrorEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.CaptureErrorEvent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isignaturecapturev1.captureerrorevent(v=AX.60)
ms:contentKeyID: 49834263
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCaptureV1.CaptureErrorEvent
dev_langs:
- CSharp
- C++
- VB
---

# CaptureErrorEvent Event


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Signature capture error event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event CaptureErrorEvent As SignatureCaptureErrorMessageEventHandler
'Usage
Dim instance As ISignatureCaptureV1
Dim handler As SignatureCaptureErrorMessageEventHandler

AddHandler instance.CaptureErrorEvent, handler
```

``` csharp
event SignatureCaptureErrorMessageEventHandler CaptureErrorEvent
```

``` c++
 event SignatureCaptureErrorMessageEventHandler^ CaptureErrorEvent {
    void add (SignatureCaptureErrorMessageEventHandler^ value);
    void remove (SignatureCaptureErrorMessageEventHandler^ value);
}
```

## See Also

#### Reference

[ISignatureCaptureV1 Interface](isignaturecapturev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

