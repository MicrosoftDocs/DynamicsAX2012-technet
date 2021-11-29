---
title: SettleInvoiceServiceResponse.InvoiceId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: InvoiceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SettleInvoiceServiceResponse.InvoiceId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.settleinvoiceserviceresponse.invoiceid(v=AX.60)
ms:contentKeyID: 62213642
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SettleInvoiceServiceResponse.InvoiceId
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the invoice identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InvoiceId As String
    Get
    Private Set
'Usage
Dim instance As SettleInvoiceServiceResponse
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

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SettleInvoiceServiceResponse Class](settleinvoiceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

