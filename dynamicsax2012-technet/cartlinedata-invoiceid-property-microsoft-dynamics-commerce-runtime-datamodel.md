---
title: CartLineData.InvoiceId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InvoiceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.InvoiceId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.invoiceid(v=AX.60)
ms:contentKeyID: 62203113
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.InvoiceId
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceId Property

Gets or sets a value indicating the invoice identifier if this instance is an invoice line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVOICEID")> _
Public Property InvoiceId As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.InvoiceId

instance.InvoiceId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVOICEID")]
public string InvoiceId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVOICEID")]
public:
property String^ InvoiceId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

