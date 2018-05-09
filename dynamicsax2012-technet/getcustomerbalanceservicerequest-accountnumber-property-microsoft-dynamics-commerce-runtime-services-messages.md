---
title: GetCustomerBalanceServiceRequest.AccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceRequest.AccountNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomerbalanceservicerequest.accountnumber(v=AX.60)
ms:contentKeyID: 62207818
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceRequest.AccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# AccountNumber Property

Gets the account number.

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
Dim instance As GetCustomerBalanceServiceRequest
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The account number.  

## See Also

#### Reference

[GetCustomerBalanceServiceRequest Class](getcustomerbalanceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

