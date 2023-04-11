---
title: CompleteCustomerAccountActivationDataRequest.Email Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Email Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CompleteCustomerAccountActivationDataRequest.Email
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.completecustomeraccountactivationdatarequest.email(v=AX.60)
ms:contentKeyID: 65315732
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CompleteCustomerAccountActivationDataRequest.Email
dev_langs:
- CSharp
- C++
- VB
---

# Email Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the e-mail address string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Email As String
    Get
    Private Set
'Usage
Dim instance As CompleteCustomerAccountActivationDataRequest
Dim value As String

value = instance.Email
```

``` csharp
[DataMemberAttribute]
public string Email { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Email {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The e-mail address.  

## See Also

#### Reference

[CompleteCustomerAccountActivationDataRequest Class](completecustomeraccountactivationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

