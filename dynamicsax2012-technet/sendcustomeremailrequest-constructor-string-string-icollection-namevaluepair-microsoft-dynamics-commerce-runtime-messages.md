---
title: SendCustomerEmailRequest Constructor (String, String, ICollection(NameValuePair)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SendCustomerEmailRequest Constructor (String, String, ICollection(NameValuePair))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerEmailRequest.#ctor(System.String,System.String,System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.NameValuePair})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.sendcustomeremailrequest.sendcustomeremailrequest(v=AX.60)
ms:contentKeyID: 49842448
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SendCustomerEmailRequest Constructor (String, String, ICollection(NameValuePair))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SendCustomerEmailRequest](sendcustomeremailrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customerAccountNumber As String, _
    emailTemplateId As String, _
    properties As ICollection(Of NameValuePair) _
)
'Usage
Dim customerAccountNumber As String
Dim emailTemplateId As String
Dim properties As ICollection(Of NameValuePair)

Dim instance As New SendCustomerEmailRequest(customerAccountNumber, _
    emailTemplateId, properties)
```

``` csharp
public SendCustomerEmailRequest(
    string customerAccountNumber,
    string emailTemplateId,
    ICollection<NameValuePair> properties
)
```

``` c++
public:
SendCustomerEmailRequest(
    String^ customerAccountNumber, 
    String^ emailTemplateId, 
    ICollection<NameValuePair^>^ properties
)
```

#### Parameters

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - emailTemplateId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - properties  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[NameValuePair](namevaluepair-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SendCustomerEmailRequest Class](sendcustomeremailrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SendCustomerEmailRequest Overload](sendcustomeremailrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

