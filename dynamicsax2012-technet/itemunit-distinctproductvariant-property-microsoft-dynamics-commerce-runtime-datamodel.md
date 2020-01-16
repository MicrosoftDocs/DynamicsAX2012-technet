---
title: ItemUnit.DistinctProductVariant Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DistinctProductVariant Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit.DistinctProductVariant
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemunit.distinctproductvariant(v=AX.60)
ms:contentKeyID: 65317149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit.DistinctProductVariant
dev_langs:
- CSharp
- C++
- VB
---

# DistinctProductVariant Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISTINCTPRODUCTVARIANT")> _
<DataMemberAttribute> _
Public Property DistinctProductVariant As Long
    Get
    Set
'Usage
Dim instance As ItemUnit
Dim value As Long

value = instance.DistinctProductVariant

instance.DistinctProductVariant = value
```

``` csharp
[ColumnAttribute("DISTINCTPRODUCTVARIANT")]
[DataMemberAttribute]
public long DistinctProductVariant { get; set; }
```

``` c++
[ColumnAttribute(L"DISTINCTPRODUCTVARIANT")]
[DataMemberAttribute]
public:
property long long DistinctProductVariant {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ItemUnit Class](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

