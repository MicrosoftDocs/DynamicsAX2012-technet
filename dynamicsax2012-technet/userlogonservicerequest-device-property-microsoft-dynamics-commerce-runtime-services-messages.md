---
title: UserLogOnServiceRequest.Device Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Device Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.Device
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonservicerequest.device(v=AX.60)
ms:contentKeyID: 62202409
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.Device
dev_langs:
- CSharp
- C++
- VB
---

# Device Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the device object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Device As Device
    Get
    Private Set
'Usage
Dim instance As UserLogOnServiceRequest
Dim value As Device

value = instance.Device
```

``` csharp
[DataMemberAttribute]
public Device Device { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Device^ Device {
    Device^ get ();
    private: void set (Device^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UserLogOnServiceRequest Class](userlogonservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

