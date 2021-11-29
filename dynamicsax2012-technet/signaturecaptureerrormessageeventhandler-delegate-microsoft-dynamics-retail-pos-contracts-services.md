---
title: SignatureCaptureErrorMessageEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SignatureCaptureErrorMessageEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.SignatureCaptureErrorMessageEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.signaturecaptureerrormessageeventhandler(v=AX.60)
ms:contentKeyID: 49851142
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.SignatureCaptureErrorMessageEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# SignatureCaptureErrorMessageEventHandler Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Signature capture device error message handler delegate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub SignatureCaptureErrorMessageEventHandler ( _
    message As String _
)
'Usage
Dim instance As New SignatureCaptureErrorMessageEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void SignatureCaptureErrorMessageEventHandler(
    string message
)
```

``` c++
public delegate void SignatureCaptureErrorMessageEventHandler(
    String^ message
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

