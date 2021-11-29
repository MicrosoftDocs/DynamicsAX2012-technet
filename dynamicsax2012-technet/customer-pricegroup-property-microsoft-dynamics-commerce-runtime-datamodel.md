---
title: Customer.PriceGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PriceGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.pricegroup(v=AX.60)
ms:contentKeyID: 49837078
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PriceGroup
dev_langs:
- CSharp
- C++
- VB
---

# PriceGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer's price group for sales price trade agreements

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEGROUP")> _
<DataMemberAttribute> _
Public Property PriceGroup As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.PriceGroup

instance.PriceGroup = value
```

``` csharp
[ColumnAttribute("PRICEGROUP")]
[DataMemberAttribute]
public string PriceGroup { get; set; }
```

``` c++
[ColumnAttribute(L"PRICEGROUP")]
[DataMemberAttribute]
public:
property String^ PriceGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The price group.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

