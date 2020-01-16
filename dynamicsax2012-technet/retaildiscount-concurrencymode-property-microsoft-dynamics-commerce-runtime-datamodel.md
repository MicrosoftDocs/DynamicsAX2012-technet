---
title: RetailDiscount.ConcurrencyMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConcurrencyMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.concurrencymode(v=AX.60)
ms:contentKeyID: 62214661
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.ConcurrencyMode
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Property

Gets or sets the concurrency mode for this discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CONCURRENCYMODE")> _
Public Property ConcurrencyMode As ConcurrencyMode
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As ConcurrencyMode

value = instance.ConcurrencyMode

instance.ConcurrencyMode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CONCURRENCYMODE")]
public ConcurrencyMode ConcurrencyMode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CONCURRENCYMODE")]
public:
property ConcurrencyMode ConcurrencyMode {
    ConcurrencyMode get ();
    void set (ConcurrencyMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

