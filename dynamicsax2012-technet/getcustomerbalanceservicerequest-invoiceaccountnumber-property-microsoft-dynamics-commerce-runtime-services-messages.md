---
title: GetCustomerBalanceServiceRequest.InvoiceAccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: InvoiceAccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceRequest.InvoiceAccountNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomerbalanceservicerequest.invoiceaccountnumber(v=AX.60)
ms:contentKeyID: 62209136
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceRequest.InvoiceAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceAccountNumber Property

Gets the invoice account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InvoiceAccountNumber As String
    Get
    Private Set
'Usage
Dim instance As GetCustomerBalanceServiceRequest
Dim value As String

value = instance.InvoiceAccountNumber
```

``` csharp
[DataMemberAttribute]
public string InvoiceAccountNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InvoiceAccountNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The invoice account number.  

## See Also

#### Reference

[GetCustomerBalanceServiceRequest Class](getcustomerbalanceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

