---
title: SettleInvoiceServiceRequest.InvoiceAmount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: InvoiceAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SettleInvoiceServiceRequest.InvoiceAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.settleinvoiceservicerequest.invoiceamount(v=AX.60)
ms:contentKeyID: 62207616
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SettleInvoiceServiceRequest.InvoiceAmount
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the invoice amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InvoiceAmount As Decimal
    Get
    Private Set
'Usage
Dim instance As SettleInvoiceServiceRequest
Dim value As Decimal

value = instance.InvoiceAmount
```

``` csharp
[DataMemberAttribute]
public decimal InvoiceAmount { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal InvoiceAmount {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SettleInvoiceServiceRequest Class](settleinvoiceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

