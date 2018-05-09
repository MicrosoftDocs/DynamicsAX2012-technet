---
title: PriceAdjustment.ConcurrencyMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConcurrencyMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.concurrencymode(v=AX.60)
ms:contentKeyID: 49834320
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ConcurrencyMode
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Property

Gets the concurrency mode for this price adjustment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CONCURRENCYMODE")> _
<DataMemberAttribute> _
Public Property ConcurrencyMode As ConcurrencyMode
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As ConcurrencyMode

value = instance.ConcurrencyMode
```

``` csharp
[ColumnAttribute("CONCURRENCYMODE")]
[DataMemberAttribute]
public ConcurrencyMode ConcurrencyMode { get; internal set; }
```

``` c++
[ColumnAttribute(L"CONCURRENCYMODE")]
[DataMemberAttribute]
public:
property ConcurrencyMode ConcurrencyMode {
    ConcurrencyMode get ();
    internal: void set (ConcurrencyMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

