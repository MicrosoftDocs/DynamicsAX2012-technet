---
title: ProcessMaskSegmentsServiceRequest.BarcodeId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: BarcodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceRequest.BarcodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.processmasksegmentsservicerequest.barcodeid(v=AX.60)
ms:contentKeyID: 62208154
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceRequest.BarcodeId
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeId Property

Gets the Barcode Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property BarcodeId As String
    Get
    Private Set
'Usage
Dim instance As ProcessMaskSegmentsServiceRequest
Dim value As String

value = instance.BarcodeId
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string BarcodeId { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ BarcodeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProcessMaskSegmentsServiceRequest Class](processmasksegmentsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

