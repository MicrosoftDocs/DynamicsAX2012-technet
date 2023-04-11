---
title: GetCustomersServiceRequest Constructor (QueryResultSettings, Int64) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCustomersServiceRequest Constructor (QueryResultSettings, Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomersservicerequest.getcustomersservicerequest(v=AX.60)
ms:contentKeyID: 65319957
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCustomersServiceRequest Constructor (QueryResultSettings, Int64)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    recordId As Long _
)
'Usage
Dim settings As QueryResultSettings
Dim recordId As Long

Dim instance As New GetCustomersServiceRequest(settings, _
    recordId)
```

``` csharp
public GetCustomersServiceRequest(
    QueryResultSettings settings,
    long recordId
)
```

``` c++
public:
GetCustomersServiceRequest(
    QueryResultSettings^ settings, 
    long long recordId
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[GetCustomersServiceRequest Class](getcustomersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCustomersServiceRequest Overload](getcustomersservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

