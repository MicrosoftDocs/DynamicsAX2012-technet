---
title: GetDeviceConfigurationDataServiceRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetDeviceConfigurationDataServiceRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceConfigurationDataServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdeviceconfigurationdataservicerequest.getdeviceconfigurationdataservicerequest(v=AX.60)
ms:contentKeyID: 65319467
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDeviceConfigurationDataServiceRequest Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetDeviceConfigurationDataServiceRequest](getdeviceconfigurationdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    storeNumber As String, _
    terminalId As String _
)
'Usage
Dim storeNumber As String
Dim terminalId As String

Dim instance As New GetDeviceConfigurationDataServiceRequest(storeNumber, _
    terminalId)
```

``` csharp
public GetDeviceConfigurationDataServiceRequest(
    string storeNumber,
    string terminalId
)
```

``` c++
public:
GetDeviceConfigurationDataServiceRequest(
    String^ storeNumber, 
    String^ terminalId
)
```

#### Parameters

  - storeNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetDeviceConfigurationDataServiceRequest Class](getdeviceconfigurationdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetDeviceConfigurationDataServiceRequest Overload](getdeviceconfigurationdataservicerequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

