---
title: ValidateHardwareStationTokenServiceResponse.Result Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Result Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceResponse.Result
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validatehardwarestationtokenserviceresponse.result(v=AX.60)
ms:contentKeyID: 65319830
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceResponse.Result
dev_langs:
- CSharp
- C++
- VB
---

# Result Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Result As ValidateHardwareStationTokenResult
    Get
    Private Set
'Usage
Dim instance As ValidateHardwareStationTokenServiceResponse
Dim value As ValidateHardwareStationTokenResult

value = instance.Result
```

``` csharp
[DataMemberAttribute]
public ValidateHardwareStationTokenResult Result { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ValidateHardwareStationTokenResult^ Result {
    ValidateHardwareStationTokenResult^ get ();
    private: void set (ValidateHardwareStationTokenResult^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidateHardwareStationTokenResult](validatehardwarestationtokenresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ValidateHardwareStationTokenServiceResponse Class](validatehardwarestationtokenserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

