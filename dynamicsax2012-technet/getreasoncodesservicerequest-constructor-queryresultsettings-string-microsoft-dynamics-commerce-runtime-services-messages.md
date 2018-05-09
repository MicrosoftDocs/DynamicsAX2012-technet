---
title: GetReasonCodesServiceRequest Constructor (QueryResultSettings, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetReasonCodesServiceRequest Constructor (QueryResultSettings, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReasonCodesServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getreasoncodesservicerequest.getreasoncodesservicerequest(v=AX.60)
ms:contentKeyID: 65316770
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReasonCodesServiceRequest Constructor (QueryResultSettings, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    reasonCodeId As String _
)
'Usage
Dim settings As QueryResultSettings
Dim reasonCodeId As String

Dim instance As New GetReasonCodesServiceRequest(settings, _
    reasonCodeId)
```

``` csharp
public GetReasonCodesServiceRequest(
    QueryResultSettings settings,
    string reasonCodeId
)
```

``` c++
public:
GetReasonCodesServiceRequest(
    QueryResultSettings^ settings, 
    String^ reasonCodeId
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetReasonCodesServiceRequest Class](getreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetReasonCodesServiceRequest Overload](getreasoncodesservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

