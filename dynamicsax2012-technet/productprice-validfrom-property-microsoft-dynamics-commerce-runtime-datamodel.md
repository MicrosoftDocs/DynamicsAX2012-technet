---
title: ProductPrice.ValidFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.ValidFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productprice.validfrom(v=AX.60)
ms:contentKeyID: 62209065
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.ValidFrom
dev_langs:
- CSharp
- C++
- VB
---

# ValidFrom Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the date that the product for this price becomes active.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDFROM")> _
<DataMemberAttribute> _
Public Property ValidFrom As DateTimeOffset
    Get
    Set
'Usage
Dim instance As ProductPrice
Dim value As DateTimeOffset

value = instance.ValidFrom

instance.ValidFrom = value
```

``` csharp
[ColumnAttribute("VALIDFROM")]
[DataMemberAttribute]
public DateTimeOffset ValidFrom { get; set; }
```

``` c++
[ColumnAttribute(L"VALIDFROM")]
[DataMemberAttribute]
public:
property DateTimeOffset ValidFrom {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ProductPrice Class](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

