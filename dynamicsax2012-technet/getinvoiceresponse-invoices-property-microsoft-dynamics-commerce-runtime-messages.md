---
title: GetInvoiceResponse.Invoices Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Invoices Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceResponse.Invoices
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getinvoiceresponse.invoices(v=AX.60)
ms:contentKeyID: 62214365
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetInvoiceResponse.Invoices
dev_langs:
- CSharp
- C++
- VB
---

# Invoices Property

Gets the invoices.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Invoices As ReadOnlyCollection(Of SalesInvoice)
    Get
    Private Set
'Usage
Dim instance As GetInvoiceResponse
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesInvoice](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetInvoiceResponse Class](getinvoiceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

