---
title: GetTrackingInformationFromCarrierServiceRequest.AdapterConfig Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AdapterConfig Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceRequest.AdapterConfig
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.gettrackinginformationfromcarrierservicerequest.adapterconfig(v=AX.60)
ms:contentKeyID: 49853059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTrackingInformationFromCarrierServiceRequest.AdapterConfig
dev_langs:
- CSharp
- C++
- VB
---

# AdapterConfig Property

Gets the adapter configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AdapterConfig As ParameterSet
    Get
    Private Set
'Usage
Dim instance As GetTrackingInformationFromCarrierServiceRequest
Dim value As ParameterSet

value = instance.AdapterConfig
```

``` csharp
[DataMemberAttribute]
public ParameterSet AdapterConfig { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ParameterSet^ AdapterConfig {
    ParameterSet^ get ();
    private: void set (ParameterSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[GetTrackingInformationFromCarrierServiceRequest Class](gettrackinginformationfromcarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

