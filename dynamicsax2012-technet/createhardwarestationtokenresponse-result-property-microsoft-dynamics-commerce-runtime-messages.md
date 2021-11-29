---
title: CreateHardwareStationTokenResponse.Result Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Result Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateHardwareStationTokenResponse.Result
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.createhardwarestationtokenresponse.result(v=AX.60)
ms:contentKeyID: 65317414
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateHardwareStationTokenResponse.Result
dev_langs:
- CSharp
- C++
- VB
---

# Result Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Result As CreateHardwareStationTokenResult
    Get
    Private Set
'Usage
Dim instance As CreateHardwareStationTokenResponse
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

[CreateHardwareStationTokenResponse Class](createhardwarestationtokenresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

