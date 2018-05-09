---
title: GetCustomersDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetCustomersDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomersDataRequest.#ctor(System.Int64,System.String,System.Int64,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcustomersdatarequest.getcustomersdatarequest(v=AX.60)
ms:contentKeyID: 65321733
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomersDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomersDataRequest Constructor

Initializes a new instance of the [GetCustomersDataRequest](getcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    recordId As Long, _
    accountNumber As String, _
    dirPartyRecId As Long, _
    partyNumber As String, _
    settings As QueryResultSettings _
)
'Usage
Dim recordId As Long
Dim accountNumber As String
Dim dirPartyRecId As Long
Dim partyNumber As String
Dim settings As QueryResultSettings

Dim instance As New GetCustomersDataRequest(recordId, _
    accountNumber, dirPartyRecId, partyNumber, _
    settings)
```

``` csharp
public GetCustomersDataRequest(
    long recordId,
    string accountNumber,
    long dirPartyRecId,
    string partyNumber,
    QueryResultSettings settings
)
```

``` c++
public:
GetCustomersDataRequest(
    long long recordId, 
    String^ accountNumber, 
    long long dirPartyRecId, 
    String^ partyNumber, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dirPartyRecId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - partyNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetCustomersDataRequest Class](getcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

