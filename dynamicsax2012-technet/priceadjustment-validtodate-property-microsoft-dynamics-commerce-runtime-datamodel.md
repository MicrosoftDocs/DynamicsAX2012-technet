---
title: PriceAdjustment.ValidToDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidToDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ValidToDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.validtodate(v=AX.60)
ms:contentKeyID: 49834883
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ValidToDate
dev_langs:
- CSharp
- C++
- VB
---

# ValidToDate Property

Gets the ending date when this rule becomes inactive.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VALIDTO")> _
Public Property ValidToDate As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As DateTimeOffset

value = instance.ValidToDate
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VALIDTO")]
public DateTimeOffset ValidToDate { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VALIDTO")]
public:
property DateTimeOffset ValidToDate {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

