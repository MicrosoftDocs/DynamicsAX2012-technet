---
title: Customer.TaxOffice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxOffice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.TaxOffice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.taxoffice(v=AX.60)
ms:contentKeyID: 62214399
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.TaxOffice
dev_langs:
- CSharp
- C++
- VB
---

# TaxOffice Property

Gets or sets the tax office.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXOFFICE")> _
Public Property TaxOffice As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.TaxOffice

instance.TaxOffice = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXOFFICE")]
public string TaxOffice { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXOFFICE")]
public:
property String^ TaxOffice {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tax office.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

