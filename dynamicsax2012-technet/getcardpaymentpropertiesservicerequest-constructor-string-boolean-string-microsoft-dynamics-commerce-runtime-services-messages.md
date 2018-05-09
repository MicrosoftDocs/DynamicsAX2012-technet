---
title: GetCardPaymentPropertiesServiceRequest Constructor (String, Boolean, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCardPaymentPropertiesServiceRequest Constructor (String, Boolean, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCardPaymentPropertiesServiceRequest.#ctor(System.String,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcardpaymentpropertiesservicerequest.getcardpaymentpropertiesservicerequest(v=AX.60)
ms:contentKeyID: 65319922
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCardPaymentPropertiesServiceRequest Constructor (String, Boolean, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    authorizationXml As String, _
    isPortable As Boolean, _
    platform As String _
)
'Usage
Dim authorizationXml As String
Dim isPortable As Boolean
Dim platform As String

Dim instance As New GetCardPaymentPropertiesServiceRequest(authorizationXml, _
    isPortable, platform)
```

``` csharp
public GetCardPaymentPropertiesServiceRequest(
    string authorizationXml,
    bool isPortable,
    string platform
)
```

``` c++
public:
GetCardPaymentPropertiesServiceRequest(
    String^ authorizationXml, 
    bool isPortable, 
    String^ platform
)
```

#### Parameters

  - authorizationXml  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isPortable  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - platform  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetCardPaymentPropertiesServiceRequest Class](getcardpaymentpropertiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCardPaymentPropertiesServiceRequest Overload](getcardpaymentpropertiesservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

