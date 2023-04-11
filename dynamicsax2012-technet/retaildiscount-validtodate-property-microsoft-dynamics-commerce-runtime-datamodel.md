---
title: RetailDiscount.ValidToDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidToDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ValidToDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.validtodate(v=AX.60)
ms:contentKeyID: 62203518
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ValidToDate
dev_langs:
- CSharp
- C++
- VB
---

# ValidToDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the ending date when this rule becomes inactive.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDTO")> _
<DataMemberAttribute> _
Public Property ValidToDate As DateTimeOffset
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As DateTimeOffset

value = instance.ValidToDate

instance.ValidToDate = value
```

``` csharp
[ColumnAttribute("VALIDTO")]
[DataMemberAttribute]
public DateTimeOffset ValidToDate { get; set; }
```

``` c++
[ColumnAttribute(L"VALIDTO")]
[DataMemberAttribute]
public:
property DateTimeOffset ValidToDate {
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

