---
title: CustomerManager.SendEmailToCustomer Method (String, String, ICollection(NameValuePair)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SendEmailToCustomer Method (String, String, ICollection(NameValuePair))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.SendEmailToCustomer(System.String,System.String,System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.NameValuePair})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.customermanager.sendemailtocustomer(v=AX.60)
ms:contentKeyID: 49843491
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SendEmailToCustomer Method (String, String, ICollection(NameValuePair))

Sends the customer an email template populated with the specified properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub SendEmailToCustomer ( _
    customerAccountNumber As String, _
    emailTemplateId As String, _
    properties As ICollection(Of NameValuePair) _
)
'Usage
Dim instance As CustomerManager
Dim customerAccountNumber As String
Dim emailTemplateId As String
Dim properties As ICollection(Of NameValuePair)

instance.SendEmailToCustomer(customerAccountNumber, _
    emailTemplateId, properties)
```

``` csharp
public void SendEmailToCustomer(
    string customerAccountNumber,
    string emailTemplateId,
    ICollection<NameValuePair> properties
)
```

``` c++
public:
void SendEmailToCustomer(
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

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[SendEmailToCustomer Overload](customermanager-sendemailtocustomer-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

