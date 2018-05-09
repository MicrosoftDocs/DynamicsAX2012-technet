---
title: Customer.InvoiceAccount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InvoiceAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.InvoiceAccount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.invoiceaccount(v=AX.60)
ms:contentKeyID: 62213895
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.InvoiceAccount
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceAccount Property

Gets or sets the invoice account.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVOICEACCOUNT")> _
<DataMemberAttribute> _
Public Property InvoiceAccount As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.InvoiceAccount

instance.InvoiceAccount = value
```

``` csharp
[ColumnAttribute("INVOICEACCOUNT")]
[DataMemberAttribute]
public string InvoiceAccount { get; set; }
```

``` c++
[ColumnAttribute(L"INVOICEACCOUNT")]
[DataMemberAttribute]
public:
property String^ InvoiceAccount {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The invoice account.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

