---
title: OrderManager.GetInvoicesBySalesId Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetInvoicesBySalesId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetInvoicesBySalesId(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getinvoicesbysalesid(v=AX.60)
ms:contentKeyID: 62210889
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetInvoicesBySalesId
dev_langs:
- CSharp
- C++
- VB
---

# GetInvoicesBySalesId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the invoices associated with the passed sales identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetInvoicesBySalesId ( _
    salesId As String _
) As ReadOnlyCollection(Of SalesInvoice)
'Usage
Dim instance As OrderManager
Dim salesId As String
Dim returnValue As ReadOnlyCollection(Of SalesInvoice)

returnValue = instance.GetInvoicesBySalesId(salesId)
```

``` csharp
public ReadOnlyCollection<SalesInvoice> GetInvoicesBySalesId(
    string salesId
)
```

``` c++
public:
ReadOnlyCollection<SalesInvoice^>^ GetInvoicesBySalesId(
    String^ salesId
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesInvoice](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The invoices for the passed sales order identifier.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

