---
title: ValidateHardwareStationTokenRequest.HardwareStationToken Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: HardwareStationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateHardwareStationTokenRequest.HardwareStationToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.validatehardwarestationtokenrequest.hardwarestationtoken(v=AX.60)
ms:contentKeyID: 62212321
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateHardwareStationTokenRequest.HardwareStationToken
dev_langs:
- CSharp
- C++
- VB
---

# HardwareStationToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the hardware station token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HardwareStationToken As String
    Get
    Set
'Usage
Dim instance As ValidateHardwareStationTokenRequest
Dim value As String

value = instance.HardwareStationToken

instance.HardwareStationToken = value
```

``` csharp
[DataMemberAttribute]
public string HardwareStationToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ HardwareStationToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The hardware station token.  

## See Also

#### Reference

[ValidateHardwareStationTokenRequest Class](validatehardwarestationtokenrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

