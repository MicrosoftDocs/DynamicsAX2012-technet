---
title: GetInvoiceRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetInvoiceRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getinvoicerequest.getinvoicerequest(v=AX.60)
ms:contentKeyID: 62215135
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetInvoiceRequest Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetInvoiceRequest](getinvoicerequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesId As String, _
    invoiceId As String _
)
'Usage
Dim salesId As String
Dim invoiceId As String

Dim instance As New GetInvoiceRequest(salesId, _
    invoiceId)
```

``` csharp
public GetInvoiceRequest(
    string salesId,
    string invoiceId
)
```

``` c++
public:
GetInvoiceRequest(
    String^ salesId, 
    String^ invoiceId
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invoiceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetInvoiceRequest Class](getinvoicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetInvoiceRequest Overload](getinvoicerequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

