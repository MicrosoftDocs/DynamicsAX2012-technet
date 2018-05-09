---
title: CreateHardwareStationTokenServiceResponse.Result Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Result Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateHardwareStationTokenServiceResponse.Result
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.createhardwarestationtokenserviceresponse.result(v=AX.60)
ms:contentKeyID: 65322623
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateHardwareStationTokenServiceResponse.Result
dev_langs:
- CSharp
- C++
- VB
---

# Result Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Result As CreateHardwareStationTokenResult
    Get
    Private Set
'Usage
Dim instance As CreateHardwareStationTokenServiceResponse
Dim value As CreateHardwareStationTokenResult

value = instance.Result
```

``` csharp
[DataMemberAttribute]
public CreateHardwareStationTokenResult Result { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CreateHardwareStationTokenResult^ Result {
    CreateHardwareStationTokenResult^ get ();
    private: void set (CreateHardwareStationTokenResult^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CreateHardwareStationTokenResult](createhardwarestationtokenresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CreateHardwareStationTokenServiceResponse Class](createhardwarestationtokenserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

