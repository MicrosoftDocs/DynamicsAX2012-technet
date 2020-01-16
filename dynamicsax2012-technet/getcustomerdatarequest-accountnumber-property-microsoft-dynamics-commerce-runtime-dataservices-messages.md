---
title: GetCustomerDataRequest.AccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: AccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerDataRequest.AccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcustomerdatarequest.accountnumber(v=AX.60)
ms:contentKeyID: 65316450
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerDataRequest.AccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# AccountNumber Property

Gets the customer account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AccountNumber As String
    Get
    Private Set
'Usage
Dim instance As GetCustomerDataRequest
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
The customer account number.  

## See Also

#### Reference

[GetCustomerDataRequest Class](getcustomerdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

