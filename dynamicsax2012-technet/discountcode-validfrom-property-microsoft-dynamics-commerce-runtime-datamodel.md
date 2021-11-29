---
title: DiscountCode.ValidFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.ValidFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.validfrom(v=AX.60)
ms:contentKeyID: 62207887
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.ValidFrom
dev_langs:
- CSharp
- C++
- VB
---

# ValidFrom Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the valid from date for the discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDFROM")> _
<DataMemberAttribute> _
Public Property ValidFrom As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As Nullable(Of DateTimeOffset)

value = instance.ValidFrom

instance.ValidFrom = value
```

``` csharp
[ColumnAttribute("VALIDFROM")]
[DataMemberAttribute]
public Nullable<DateTimeOffset> ValidFrom { get; set; }
```

``` c++
[ColumnAttribute(L"VALIDFROM")]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> ValidFrom {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[DiscountCode Class](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

