---
title: ItemReservation.ExpireDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpireDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation.ExpireDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemreservation.expiredatetime(v=AX.60)
ms:contentKeyID: 49831407
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation.ExpireDateTime
dev_langs:
- CSharp
- C++
- VB
---

# ExpireDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the expire date time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EXPIREDATETIME")> _
<DataMemberAttribute> _
Public Property ExpireDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As ItemReservation
Dim value As DateTimeOffset

value = instance.ExpireDateTime

instance.ExpireDateTime = value
```

``` csharp
[ColumnAttribute("EXPIREDATETIME")]
[DataMemberAttribute]
public DateTimeOffset ExpireDateTime { get; set; }
```

``` c++
[ColumnAttribute(L"EXPIREDATETIME")]
[DataMemberAttribute]
public:
property DateTimeOffset ExpireDateTime {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
The expire date time.  

## See Also

#### Reference

[ItemReservation Class](itemreservation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

