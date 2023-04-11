---
title: GetCustomersServiceRequest.CustomerPartyNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomerPartyNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest.CustomerPartyNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomersservicerequest.customerpartynumber(v=AX.60)
ms:contentKeyID: 62211707
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceRequest.CustomerPartyNumber
dev_langs:
- CSharp
- C++
- VB
---

# CustomerPartyNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer party number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerPartyNumber As String
    Get
    Private Set
'Usage
Dim instance As GetCustomersServiceRequest
Dim value As String

value = instance.CustomerPartyNumber
```

``` csharp
[DataMemberAttribute]
public string CustomerPartyNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerPartyNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The customer party number.  

## See Also

#### Reference

[GetCustomersServiceRequest Class](getcustomersservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

