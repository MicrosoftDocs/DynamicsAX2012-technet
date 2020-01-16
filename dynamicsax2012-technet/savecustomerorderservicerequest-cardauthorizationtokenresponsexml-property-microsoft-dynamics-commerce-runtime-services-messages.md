---
title: SaveCustomerOrderServiceRequest.CardAuthorizationTokenResponseXml Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CardAuthorizationTokenResponseXml Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest.CardAuthorizationTokenResponseXml
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecustomerorderservicerequest.cardauthorizationtokenresponsexml(v=AX.60)
ms:contentKeyID: 62209912
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest.CardAuthorizationTokenResponseXml
dev_langs:
- CSharp
- C++
- VB
---

# CardAuthorizationTokenResponseXml Property

Gets or sets the card token response XML.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardAuthorizationTokenResponseXml As String
    Get
    Set
'Usage
Dim instance As SaveCustomerOrderServiceRequest
Dim value As String

value = instance.CardAuthorizationTokenResponseXml

instance.CardAuthorizationTokenResponseXml = value
```

``` csharp
[DataMemberAttribute]
public string CardAuthorizationTokenResponseXml { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CardAuthorizationTokenResponseXml {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SaveCustomerOrderServiceRequest Class](savecustomerorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

