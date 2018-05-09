---
title: ValidateHardwareStationTokenResponse.Result Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Result Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateHardwareStationTokenResponse.Result
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.validatehardwarestationtokenresponse.result(v=AX.60)
ms:contentKeyID: 65316631
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateHardwareStationTokenResponse.Result
dev_langs:
- CSharp
- C++
- VB
---

# Result Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Result As ValidateHardwareStationTokenResult
    Get
    Private Set
'Usage
Dim instance As ValidateHardwareStationTokenResponse
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

[ValidateHardwareStationTokenResponse Class](validatehardwarestationtokenresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

