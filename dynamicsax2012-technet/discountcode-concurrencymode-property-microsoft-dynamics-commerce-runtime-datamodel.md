---
title: DiscountCode.ConcurrencyMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConcurrencyMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.concurrencymode(v=AX.60)
ms:contentKeyID: 62206458
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.ConcurrencyMode
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Property

Gets or sets the concurrency mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CONCURRENCYMODE")> _
Public Property ConcurrencyMode As Integer
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As Integer

value = instance.ConcurrencyMode

instance.ConcurrencyMode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CONCURRENCYMODE")]
public int ConcurrencyMode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CONCURRENCYMODE")]
public:
property int ConcurrencyMode {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DiscountCode Class](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

