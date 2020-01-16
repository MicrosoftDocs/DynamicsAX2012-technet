---
title: PriceGroup.PriceGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceGroup.PriceGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pricegroup.pricegroupid(v=AX.60)
ms:contentKeyID: 49826699
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceGroup.PriceGroupId
dev_langs:
- CSharp
- C++
- VB
---

# PriceGroupId Property

Gets the price group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEGROUP")> _
<DataMemberAttribute> _
Public Property PriceGroupId As Long
    Get
    Set
'Usage
Dim instance As PriceGroup
Dim value As Long

value = instance.PriceGroupId

instance.PriceGroupId = value
```

``` csharp
[ColumnAttribute("PRICEGROUP")]
[DataMemberAttribute]
public long PriceGroupId { get; set; }
```

``` c++
[ColumnAttribute(L"PRICEGROUP")]
[DataMemberAttribute]
public:
property long long PriceGroupId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[PriceGroup Class](pricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

