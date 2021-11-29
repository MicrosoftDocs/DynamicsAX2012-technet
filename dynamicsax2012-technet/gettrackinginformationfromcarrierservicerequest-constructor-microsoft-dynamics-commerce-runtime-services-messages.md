---
title: GetTrackingInformationFromCarrierServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetTrackingInformationFromCarrierServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.ParameterSet,System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.gettrackinginformationfromcarrierservicerequest.gettrackinginformationfromcarrierservicerequest(v=AX.60)
ms:contentKeyID: 65317165
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetTrackingInformationFromCarrierServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    adapterConfig As ParameterSet, _
    trackingNumbers As IEnumerable(Of String) _
)
'Usage
Dim adapterConfig As ParameterSet
Dim trackingNumbers As IEnumerable(Of String)

Dim instance As New GetTrackingInformationFromCarrierServiceRequest(adapterConfig, _
    trackingNumbers)
```

``` csharp
public GetTrackingInformationFromCarrierServiceRequest(
    ParameterSet adapterConfig,
    IEnumerable<string> trackingNumbers
)
```

``` c++
public:
GetTrackingInformationFromCarrierServiceRequest(
    ParameterSet^ adapterConfig, 
    IEnumerable<String^>^ trackingNumbers
)
```

#### Parameters

  - adapterConfig  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - trackingNumbers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetTrackingInformationFromCarrierServiceRequest Class](gettrackinginformationfromcarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

