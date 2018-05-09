---
title: SalesInvoice.SalesType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.SalesType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice.salestype(v=AX.60)
ms:contentKeyID: 62208658
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.SalesType
dev_langs:
- CSharp
- C++
- VB
---

# SalesType Property

Gets or sets the sales identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALESTYPE")> _
<DataMemberAttribute> _
Public Property SalesType As SalesInvoiceType
    Get
    Set
'Usage
Dim instance As SalesInvoice
Dim value As SalesInvoiceType

value = instance.SalesType

instance.SalesType = value
```

``` csharp
[ColumnAttribute("SALESTYPE")]
[DataMemberAttribute]
public SalesInvoiceType SalesType { get; set; }
```

``` c++
[ColumnAttribute(L"SALESTYPE")]
[DataMemberAttribute]
public:
property SalesInvoiceType SalesType {
    SalesInvoiceType get ();
    void set (SalesInvoiceType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceType](salesinvoicetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales identifier.  

## See Also

#### Reference

[SalesInvoice Class](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

