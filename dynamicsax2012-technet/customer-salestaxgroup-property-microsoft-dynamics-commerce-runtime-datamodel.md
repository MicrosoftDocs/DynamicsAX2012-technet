---
title: Customer.SalesTaxGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTaxGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.SalesTaxGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.salestaxgroup(v=AX.60)
ms:contentKeyID: 62209434
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.SalesTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesTaxGroup As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.SalesTaxGroup

instance.SalesTaxGroup = value
```

``` csharp
[DataMemberAttribute]
public string SalesTaxGroup { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SalesTaxGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The sales tax group.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

