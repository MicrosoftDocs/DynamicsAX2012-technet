---
title: DiscountLine.ConcurrencyMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConcurrencyMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.concurrencymode(v=AX.60)
ms:contentKeyID: 49851707
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.ConcurrencyMode
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the concurrency mode for the offer this discount line came from

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ConcurrencyMode As ConcurrencyMode
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As ConcurrencyMode

value = instance.ConcurrencyMode

instance.ConcurrencyMode = value
```

``` csharp
[IgnoreDataMemberAttribute]
public ConcurrencyMode ConcurrencyMode { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
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

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

