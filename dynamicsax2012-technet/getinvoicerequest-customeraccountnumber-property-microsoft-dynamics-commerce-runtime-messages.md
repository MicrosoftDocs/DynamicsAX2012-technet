---
title: GetInvoiceRequest.CustomerAccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CustomerAccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceRequest.CustomerAccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getinvoicerequest.customeraccountnumber(v=AX.60)
ms:contentKeyID: 62211534
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceRequest.CustomerAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccountNumber Property

Gets or sets the Customer Account Number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerAccountNumber As String
    Get
    Set
'Usage
Dim instance As GetInvoiceRequest
Dim value As String

value = instance.CustomerAccountNumber

instance.CustomerAccountNumber = value
```

``` csharp
[DataMemberAttribute]
public string CustomerAccountNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerAccountNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetInvoiceRequest Class](getinvoicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

