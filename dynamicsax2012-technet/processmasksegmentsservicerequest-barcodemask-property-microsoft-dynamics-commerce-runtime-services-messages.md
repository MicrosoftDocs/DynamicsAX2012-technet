---
title: ProcessMaskSegmentsServiceRequest.BarcodeMask Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: BarcodeMask Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceRequest.BarcodeMask
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.processmasksegmentsservicerequest.barcodemask(v=AX.60)
ms:contentKeyID: 62212342
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceRequest.BarcodeMask
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeMask Property

Gets the BarcodeMask segment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property BarcodeMask As BarcodeMask
    Get
    Private Set
'Usage
Dim instance As ProcessMaskSegmentsServiceRequest
Dim value As BarcodeMask

value = instance.BarcodeMask
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public BarcodeMask BarcodeMask { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property BarcodeMask^ BarcodeMask {
    BarcodeMask^ get ();
    private: void set (BarcodeMask^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask](barcodemask-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [BarcodeMask](barcodemask-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProcessMaskSegmentsServiceRequest Class](processmasksegmentsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

