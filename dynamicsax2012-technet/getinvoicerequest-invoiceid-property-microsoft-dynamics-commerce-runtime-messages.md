---
title: GetInvoiceRequest.InvoiceId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: InvoiceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceRequest.InvoiceId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getinvoicerequest.invoiceid(v=AX.60)
ms:contentKeyID: 62208901
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceRequest.InvoiceId
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the invoice Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InvoiceId As String
    Get
    Set
'Usage
Dim instance As GetInvoiceRequest
Dim value As String

value = instance.InvoiceId

instance.InvoiceId = value
```

``` csharp
[DataMemberAttribute]
public string InvoiceId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InvoiceId {
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

