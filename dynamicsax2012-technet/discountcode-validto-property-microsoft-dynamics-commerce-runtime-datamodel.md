---
title: DiscountCode.ValidTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.ValidTo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.validto(v=AX.60)
ms:contentKeyID: 62213978
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.ValidTo
dev_langs:
- CSharp
- C++
- VB
---

# ValidTo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the valid to date for the discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDTO")> _
<DataMemberAttribute> _
Public Property ValidTo As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As Nullable(Of DateTimeOffset)

value = instance.ValidTo

instance.ValidTo = value
```

``` csharp
[ColumnAttribute("VALIDTO")]
[DataMemberAttribute]
public Nullable<DateTimeOffset> ValidTo { get; set; }
```

``` c++
[ColumnAttribute(L"VALIDTO")]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> ValidTo {
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

