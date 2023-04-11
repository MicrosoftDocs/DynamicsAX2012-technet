---
title: SendEmailServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SendEmailServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.#ctor(System.String,System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.NameValuePair},System.String,System.Object,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.sendemailservicerequest.sendemailservicerequest(v=AX.60)
ms:contentKeyID: 65321501
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SendEmailServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    emailAddress As String, _
    mappings As ICollection(Of NameValuePair), _
    language As String, _
    xmlData As Object, _
    emailId As String _
)
'Usage
Dim emailAddress As String
Dim mappings As ICollection(Of NameValuePair)
Dim language As String
Dim xmlData As Object
Dim emailId As String

Dim instance As New SendEmailServiceRequest(emailAddress, _
    mappings, language, xmlData, emailId)
```

``` csharp
public SendEmailServiceRequest(
    string emailAddress,
    ICollection<NameValuePair> mappings,
    string language,
    Object xmlData,
    string emailId
)
```

``` c++
public:
SendEmailServiceRequest(
    String^ emailAddress, 
    ICollection<NameValuePair^>^ mappings, 
    String^ language, 
    Object^ xmlData, 
    String^ emailId
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - mappings  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[NameValuePair](namevaluepair-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - language  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - xmlData  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - emailId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SendEmailServiceRequest Class](sendemailservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

