---
title: GetPricesServiceRequest.CustomerAccount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomerAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.CustomerAccount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpricesservicerequest.customeraccount(v=AX.60)
ms:contentKeyID: 62212374
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.CustomerAccount
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer account number for customer-specific prices. Optional.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerAccount As String
    Get
    Private Set
'Usage
Dim instance As GetPricesServiceRequest
Dim value As String

value = instance.CustomerAccount
```

``` csharp
[DataMemberAttribute]
public string CustomerAccount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerAccount {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetPricesServiceRequest Class](getpricesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

