---
title: ProcessMaskSegmentsServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ProcessMaskSegmentsServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.processmasksegmentsservicerequest.processmasksegmentsservicerequest(v=AX.60)
ms:contentKeyID: 65315815
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ProcessMaskSegmentsServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    barcodeId As String, _
    barcodeMask As BarcodeMask _
)
'Usage
Dim barcodeId As String
Dim barcodeMask As BarcodeMask

Dim instance As New ProcessMaskSegmentsServiceRequest(barcodeId, _
    barcodeMask)
```

``` csharp
public ProcessMaskSegmentsServiceRequest(
    string barcodeId,
    BarcodeMask barcodeMask
)
```

``` c++
public:
ProcessMaskSegmentsServiceRequest(
    String^ barcodeId, 
    BarcodeMask^ barcodeMask
)
```

#### Parameters

  - barcodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - barcodeMask  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask](barcodemask-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProcessMaskSegmentsServiceRequest Class](processmasksegmentsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

