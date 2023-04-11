---
title: ValidateCustomerAccountPaymentRealtimeRequest.AccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateCustomerAccountPaymentRealtimeRequest.AccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validatecustomeraccountpaymentrealtimerequest.accountnumber(v=AX.60)
ms:contentKeyID: 65318335
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateCustomerAccountPaymentRealtimeRequest.AccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# AccountNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AccountNumber As String
    Get
    Private Set
'Usage
Dim instance As ValidateCustomerAccountPaymentRealtimeRequest
Dim value As String

value = instance.AccountNumber
```

``` csharp
[DataMemberAttribute]
public string AccountNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ AccountNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ValidateCustomerAccountPaymentRealtimeRequest Class](validatecustomeraccountpaymentrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

