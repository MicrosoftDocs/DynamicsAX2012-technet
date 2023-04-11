---
title: GetDeviceConfigurationDataServiceRequest Constructor (Int64, String) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetDeviceConfigurationDataServiceRequest Constructor (Int64, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceConfigurationDataServiceRequest.#ctor(System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdeviceconfigurationdataservicerequest.getdeviceconfigurationdataservicerequest(v=AX.60)
ms:contentKeyID: 65321272
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDeviceConfigurationDataServiceRequest Constructor (Int64, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetDeviceConfigurationDataServiceRequest](getdeviceconfigurationdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    terminalId As String _
)
'Usage
Dim channelId As Long
Dim terminalId As String

Dim instance As New GetDeviceConfigurationDataServiceRequest(channelId, _
    terminalId)
```

``` csharp
public GetDeviceConfigurationDataServiceRequest(
    long channelId,
    string terminalId
)
```

``` c++
public:
GetDeviceConfigurationDataServiceRequest(
    long long channelId, 
    String^ terminalId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetDeviceConfigurationDataServiceRequest Class](getdeviceconfigurationdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetDeviceConfigurationDataServiceRequest Overload](getdeviceconfigurationdataservicerequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

