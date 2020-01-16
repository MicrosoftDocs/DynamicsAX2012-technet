---
title: SaveCustomerAccountActivationServiceRequest.Status Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerAccountActivationServiceRequest.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecustomeraccountactivationservicerequest.status(v=AX.60)
ms:contentKeyID: 62206540
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerAccountActivationServiceRequest.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property

Gets the status of the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Status As Integer
    Get
    Private Set
'Usage
Dim instance As SaveCustomerAccountActivationServiceRequest
Dim value As Integer

value = instance.Status
```

``` csharp
[DataMemberAttribute]
public int Status { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int Status {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SaveCustomerAccountActivationServiceRequest Class](savecustomeraccountactivationservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

