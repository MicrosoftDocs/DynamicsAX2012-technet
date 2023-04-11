---
title: ProcessMaskSegmentsServiceResponse.Barcode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Barcode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceResponse.Barcode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.processmasksegmentsserviceresponse.barcode(v=AX.60)
ms:contentKeyID: 62211056
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProcessMaskSegmentsServiceResponse.Barcode
dev_langs:
- CSharp
- C++
- VB
---

# Barcode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Barcode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Barcode As Barcode
    Get
    Private Set
'Usage
Dim instance As ProcessMaskSegmentsServiceResponse
Dim value As Barcode

value = instance.Barcode
```

``` csharp
[DataMemberAttribute]
public Barcode Barcode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Barcode^ Barcode {
    Barcode^ get ();
    private: void set (Barcode^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Barcode](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProcessMaskSegmentsServiceResponse Class](processmasksegmentsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

