---
title: GetBarcodeTypeServiceRequest.BarcodeId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: BarcodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetBarcodeTypeServiceRequest.BarcodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getbarcodetypeservicerequest.barcodeid(v=AX.60)
ms:contentKeyID: 62213430
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetBarcodeTypeServiceRequest.BarcodeId
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Barcode value.

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
Dim instance As GetBarcodeTypeServiceRequest
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

[GetBarcodeTypeServiceRequest Class](getbarcodetypeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

