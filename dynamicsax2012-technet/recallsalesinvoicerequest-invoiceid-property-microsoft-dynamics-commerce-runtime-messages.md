---
title: RecallSalesInvoiceRequest.InvoiceId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: InvoiceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.RecallSalesInvoiceRequest.InvoiceId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.recallsalesinvoicerequest.invoiceid(v=AX.60)
ms:contentKeyID: 62209415
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.RecallSalesInvoiceRequest.InvoiceId
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceId Property

Gets the invoice ID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InvoiceId As String
    Get
    Private Set
'Usage
Dim instance As RecallSalesInvoiceRequest
Dim value As String

value = instance.InvoiceId
```

``` csharp
[DataMemberAttribute]
public string InvoiceId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InvoiceId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RecallSalesInvoiceRequest Class](recallsalesinvoicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

