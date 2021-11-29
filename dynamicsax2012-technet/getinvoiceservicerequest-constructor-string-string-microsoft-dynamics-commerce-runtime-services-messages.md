---
title: GetInvoiceServiceRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetInvoiceServiceRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInvoiceServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getinvoiceservicerequest.getinvoiceservicerequest(v=AX.60)
ms:contentKeyID: 65316115
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetInvoiceServiceRequest Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

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

Dim instance As New GetInvoiceServiceRequest(salesId, _
    invoiceId)
```

``` csharp
public GetInvoiceServiceRequest(
    string salesId,
    string invoiceId
)
```

``` c++
public:
GetInvoiceServiceRequest(
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

[GetInvoiceServiceRequest Class](getinvoiceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetInvoiceServiceRequest Overload](getinvoiceservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

