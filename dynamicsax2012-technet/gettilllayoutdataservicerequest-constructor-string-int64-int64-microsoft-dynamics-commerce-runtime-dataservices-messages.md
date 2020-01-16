---
title: GetTillLayoutDataServiceRequest Constructor (String, Int64, Int64) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetTillLayoutDataServiceRequest Constructor (String, Int64, Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTillLayoutDataServiceRequest.#ctor(System.String,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettilllayoutdataservicerequest.gettilllayoutdataservicerequest(v=AX.60)
ms:contentKeyID: 65321466
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetTillLayoutDataServiceRequest Constructor (String, Int64, Int64)

Initializes a new instance of the [GetTillLayoutDataServiceRequest](gettilllayoutdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    userId As String, _
    terminalId As Long, _
    channelId As Long _
)
'Usage
Dim userId As String
Dim terminalId As Long
Dim channelId As Long

Dim instance As New GetTillLayoutDataServiceRequest(userId, _
    terminalId, channelId)
```

``` csharp
public GetTillLayoutDataServiceRequest(
    string userId,
    long terminalId,
    long channelId
)
```

``` c++
public:
GetTillLayoutDataServiceRequest(
    String^ userId, 
    long long terminalId, 
    long long channelId
)
```

#### Parameters

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[GetTillLayoutDataServiceRequest Class](gettilllayoutdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetTillLayoutDataServiceRequest Overload](gettilllayoutdataservicerequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

