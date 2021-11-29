---
title: CustomerManager.SendAccountActivationEmailToCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SendAccountActivationEmailToCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.SendAccountActivationEmailToCustomer(System.String,System.String,System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.NameValuePair})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.customermanager.sendaccountactivationemailtocustomer(v=AX.60)
ms:contentKeyID: 62212850
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.SendAccountActivationEmailToCustomer
dev_langs:
- CSharp
- C++
- VB
---

# SendAccountActivationEmailToCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sends the customer an email template populated with the specified properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub SendAccountActivationEmailToCustomer ( _
    emailAddress As String, _
    emailTemplateId As String, _
    properties As ICollection(Of NameValuePair) _
)
'Usage
Dim instance As CustomerManager
Dim emailAddress As String
Dim emailTemplateId As String
Dim properties As ICollection(Of NameValuePair)

instance.SendAccountActivationEmailToCustomer(emailAddress, _
    emailTemplateId, properties)
```

``` csharp
public void SendAccountActivationEmailToCustomer(
    string emailAddress,
    string emailTemplateId,
    ICollection<NameValuePair> properties
)
```

``` c++
public:
void SendAccountActivationEmailToCustomer(
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

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

