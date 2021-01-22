---
title: Customer.TaxExemptNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxExemptNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.TaxExemptNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.taxexemptnumber(v=AX.60)
ms:contentKeyID: 62209892
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.TaxExemptNumber
dev_langs:
- CSharp
- C++
- VB
---

# TaxExemptNumber Property

Gets or sets the tax exempt number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXLICENSENUM")> _
<DataMemberAttribute> _
Public Property TaxExemptNumber As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.TaxExemptNumber

instance.TaxExemptNumber = value
```

``` csharp
[ColumnAttribute("TAXLICENSENUM")]
[DataMemberAttribute]
public string TaxExemptNumber { get; set; }
```

``` c++
[ColumnAttribute(L"TAXLICENSENUM")]
[DataMemberAttribute]
public:
property String^ TaxExemptNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tax exempt number.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

