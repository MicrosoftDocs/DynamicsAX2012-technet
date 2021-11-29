---
title: PriceAdjustmentPriceLine.Concurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Concurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustmentPriceLine.Concurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustmentpriceline.concurrency(v=AX.60)
ms:contentKeyID: 62206423
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustmentPriceLine.Concurrency
dev_langs:
- CSharp
- C++
- VB
---

# Concurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the concurrency mode of the price adjustment line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CONCURRENCY")> _
<DataMemberAttribute> _
Public Property Concurrency As ConcurrencyMode
    Get
    Set
'Usage
Dim instance As PriceAdjustmentPriceLine
Dim value As ConcurrencyMode

value = instance.Concurrency

instance.Concurrency = value
```

``` csharp
[ColumnAttribute("CONCURRENCY")]
[DataMemberAttribute]
public ConcurrencyMode Concurrency { get; set; }
```

``` c++
[ColumnAttribute(L"CONCURRENCY")]
[DataMemberAttribute]
public:
property ConcurrencyMode Concurrency {
    ConcurrencyMode get ();
    void set (ConcurrencyMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PriceAdjustmentPriceLine Class](priceadjustmentpriceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

