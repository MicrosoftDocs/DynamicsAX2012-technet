---
title: GetInvoiceServiceResponse.Invoices Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Invoices Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInvoiceServiceResponse.Invoices
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getinvoiceserviceresponse.invoices(v=AX.60)
ms:contentKeyID: 62207298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInvoiceServiceResponse.Invoices
dev_langs:
- CSharp
- C++
- VB
---

# Invoices Property

Gets the invoices.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Invoices As ReadOnlyCollection(Of SalesInvoice)
    Get
    Private Set
'Usage
Dim instance As GetInvoiceServiceResponse
Dim value As ReadOnlyCollection(Of SalesInvoice)

value = instance.Invoices
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SalesInvoice> Invoices { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SalesInvoice^>^ Invoices {
    ReadOnlyCollection<SalesInvoice^>^ get ();
    private: void set (ReadOnlyCollection<SalesInvoice^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesInvoice](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetInvoiceServiceResponse Class](getinvoiceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

