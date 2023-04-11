---
title: GetCustomersServiceRequest Constructor (QueryResultSettings, Int64, String, Int64, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCustomersServiceRequest Constructor (QueryResultSettings, Int64, String, Int64, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Int64,System.String,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomersservicerequest.getcustomersservicerequest(v=AX.60)
ms:contentKeyID: 65319113
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCustomersServiceRequest Constructor (QueryResultSettings, Int64, String, Int64, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    recordId As Long, _
    accountNumber As String, _
    partyRecordId As Long, _
    partyNumber As String _
)
'Usage
Dim settings As QueryResultSettings
Dim recordId As Long
Dim accountNumber As String
Dim partyRecordId As Long
Dim partyNumber As String

Dim instance As New GetCustomersServiceRequest(settings, _
    recordId, accountNumber, partyRecordId, _
    partyNumber)
```

``` csharp
public GetCustomersServiceRequest(
    QueryResultSettings settings,
    long recordId,
    string accountNumber,
    long partyRecordId,
    string partyNumber
)
```

``` c++
public:
GetCustomersServiceRequest(
    QueryResultSettings^ settings, 
    long long recordId, 
    String^ accountNumber, 
    long long partyRecordId, 
    String^ partyNumber
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - partyRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - partyNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetCustomersServiceRequest Class](getcustomersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCustomersServiceRequest Overload](getcustomersservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

