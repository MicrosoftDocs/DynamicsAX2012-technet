---
title: Customer.VatNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VatNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.VatNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.vatnumber(v=AX.60)
ms:contentKeyID: 62202593
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.VatNumber
dev_langs:
- CSharp
- C++
- VB
---

# VatNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the VAT number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VATNUM")> _
<DataMemberAttribute> _
Public Property VatNumber As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.VatNumber

instance.VatNumber = value
```

``` csharp
[ColumnAttribute("VATNUM")]
[DataMemberAttribute]
public string VatNumber { get; set; }
```

``` c++
[ColumnAttribute(L"VATNUM")]
[DataMemberAttribute]
public:
property String^ VatNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The VAT number.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

