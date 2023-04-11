---
title: GetInvoiceResponse Constructor (IEnumerable(SalesInvoice)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetInvoiceResponse Constructor (IEnumerable(SalesInvoice))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getinvoiceresponse.getinvoiceresponse(v=AX.60)
ms:contentKeyID: 62208848
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetInvoiceResponse Constructor (IEnumerable(SalesInvoice))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetInvoiceResponse](getinvoiceresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    invoices As IEnumerable(Of SalesInvoice) _
)
'Usage
Dim invoices As IEnumerable(Of SalesInvoice)

Dim instance As New GetInvoiceResponse(invoices)
```

``` csharp
public GetInvoiceResponse(
    IEnumerable<SalesInvoice> invoices
)
```

``` c++
public:
GetInvoiceResponse(
    IEnumerable<SalesInvoice^>^ invoices
)
```

#### Parameters

  - invoices  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesInvoice](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetInvoiceResponse Class](getinvoiceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetInvoiceResponse Overload](getinvoiceresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

