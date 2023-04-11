---
title: RetailDiscount.ValidFromDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidFromDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ValidFromDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.validfromdate(v=AX.60)
ms:contentKeyID: 62206527
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ValidFromDate
dev_langs:
- CSharp
- C++
- VB
---

# ValidFromDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the starting date when this rule becomes active.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDFROM")> _
<DataMemberAttribute> _
Public Property ValidFromDate As DateTimeOffset
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As DateTimeOffset

value = instance.ValidFromDate

instance.ValidFromDate = value
```

``` csharp
[ColumnAttribute("VALIDFROM")]
[DataMemberAttribute]
public DateTimeOffset ValidFromDate { get; set; }
```

``` c++
[ColumnAttribute(L"VALIDFROM")]
[DataMemberAttribute]
public:
property DateTimeOffset ValidFromDate {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

