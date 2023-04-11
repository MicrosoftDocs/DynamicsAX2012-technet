---
title: GetDeviceDataServiceRequest Constructor (String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetDeviceDataServiceRequest Constructor (String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceDataServiceRequest.#ctor(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdevicedataservicerequest.getdevicedataservicerequest(v=AX.60)
ms:contentKeyID: 65320336
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDeviceDataServiceRequest Constructor (String, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetDeviceDataServiceRequest](getdevicedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deviceNumber As String, _
    isActivatedOnly As Boolean _
)
'Usage
Dim deviceNumber As String
Dim isActivatedOnly As Boolean

Dim instance As New GetDeviceDataServiceRequest(deviceNumber, _
    isActivatedOnly)
```

``` csharp
public GetDeviceDataServiceRequest(
    string deviceNumber,
    bool isActivatedOnly
)
```

``` c++
public:
GetDeviceDataServiceRequest(
    String^ deviceNumber, 
    bool isActivatedOnly
)
```

#### Parameters

  - deviceNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isActivatedOnly  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetDeviceDataServiceRequest Class](getdevicedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetDeviceDataServiceRequest Overload](getdevicedataservicerequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

