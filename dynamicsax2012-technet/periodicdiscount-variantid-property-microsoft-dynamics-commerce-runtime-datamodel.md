---
title: PeriodicDiscount.VariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.VariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.variantid(v=AX.60)
ms:contentKeyID: 65320638
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.VariantId
dev_langs:
- CSharp
- C++
- VB
---

# VariantId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VARIANT")> _
<DataMemberAttribute> _
Public Property VariantId As Long
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Long

value = instance.VariantId
```

``` csharp
[ColumnAttribute("VARIANT")]
[DataMemberAttribute]
public long VariantId { get; internal set; }
```

``` c++
[ColumnAttribute(L"VARIANT")]
[DataMemberAttribute]
public:
property long long VariantId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

