---
title: GetCustomerBalanceRequest.InvoiceAccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: InvoiceAccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerBalanceRequest.InvoiceAccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomerbalancerequest.invoiceaccountnumber(v=AX.60)
ms:contentKeyID: 62214904
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerBalanceRequest.InvoiceAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceAccountNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the invoice account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InvoiceAccountNumber As String
    Get
    Set
'Usage
Dim instance As GetCustomerBalanceRequest
Dim value As String

value = instance.InvoiceAccountNumber

instance.InvoiceAccountNumber = value
```

``` csharp
[DataMemberAttribute]
public string InvoiceAccountNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InvoiceAccountNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The invoice account number.  

## See Also

#### Reference

[GetCustomerBalanceRequest Class](getcustomerbalancerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

