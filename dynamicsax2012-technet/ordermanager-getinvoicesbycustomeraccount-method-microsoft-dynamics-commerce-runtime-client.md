---
title: OrderManager.GetInvoicesByCustomerAccount Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetInvoicesByCustomerAccount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetInvoicesByCustomerAccount(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getinvoicesbycustomeraccount(v=AX.60)
ms:contentKeyID: 62214856
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetInvoicesByCustomerAccount
dev_langs:
- CSharp
- C++
- VB
---

# GetInvoicesByCustomerAccount Method

Gets the invoices associated with the given customer account identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetInvoicesByCustomerAccount ( _
    customerAccount As String _
) As ReadOnlyCollection(Of SalesInvoice)
'Usage
Dim instance As OrderManager
Dim customerAccount As String
Dim returnValue As ReadOnlyCollection(Of SalesInvoice)

returnValue = instance.GetInvoicesByCustomerAccount(customerAccount)
```

``` csharp
public ReadOnlyCollection<SalesInvoice> GetInvoicesByCustomerAccount(
    string customerAccount
)
```

``` c++
public:
ReadOnlyCollection<SalesInvoice^>^ GetInvoicesByCustomerAccount(
    String^ customerAccount
)
```

#### Parameters

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesInvoice](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The invoices for the given customer account.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/3w1b3114(v=ax.60)">ArgumentException</a></td>
<td><p>Thrown if customerAccount is null or empty.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

