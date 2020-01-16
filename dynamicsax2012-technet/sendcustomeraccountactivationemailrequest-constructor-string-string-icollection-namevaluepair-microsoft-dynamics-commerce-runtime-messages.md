---
title: SendCustomerAccountActivationEmailRequest Constructor (String, String, ICollection(NameValuePair)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SendCustomerAccountActivationEmailRequest Constructor (String, String, ICollection(NameValuePair))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerAccountActivationEmailRequest.#ctor(System.String,System.String,System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.NameValuePair})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.sendcustomeraccountactivationemailrequest.sendcustomeraccountactivationemailrequest(v=AX.60)
ms:contentKeyID: 62212198
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SendCustomerAccountActivationEmailRequest Constructor (String, String, ICollection(NameValuePair))

Initializes a new instance of the [SendCustomerAccountActivationEmailRequest](sendcustomeraccountactivationemailrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    emailAddress As String, _
    emailTemplateId As String, _
    properties As ICollection(Of NameValuePair) _
)
'Usage
Dim emailAddress As String
Dim emailTemplateId As String
Dim properties As ICollection(Of NameValuePair)

Dim instance As New SendCustomerAccountActivationEmailRequest(emailAddress, _
    emailTemplateId, properties)
```

``` csharp
public SendCustomerAccountActivationEmailRequest(
    string emailAddress,
    string emailTemplateId,
    ICollection<NameValuePair> properties
)
```

``` c++
public:
SendCustomerAccountActivationEmailRequest(
    String^ emailAddress, 
    String^ emailTemplateId, 
    ICollection<NameValuePair^>^ properties
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - emailTemplateId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - properties  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[NameValuePair](namevaluepair-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SendCustomerAccountActivationEmailRequest Class](sendcustomeraccountactivationemailrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SendCustomerAccountActivationEmailRequest Overload](sendcustomeraccountactivationemailrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

