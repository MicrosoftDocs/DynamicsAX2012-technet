---
title: ItemDimensions.NetWeight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetWeight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions.NetWeight
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemdimensions.netweight(v=AX.60)
ms:contentKeyID: 65318626
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions.NetWeight
dev_langs:
- CSharp
- C++
- VB
---

# NetWeight Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NETWEIGHT")> _
Public ReadOnly Property NetWeight As Decimal
    Get
'Usage
Dim instance As ItemDimensions
Dim value As Decimal

value = instance.NetWeight
```

``` csharp
[ColumnAttribute("NETWEIGHT")]
public decimal NetWeight { get; }
```

``` c++
[ColumnAttribute(L"NETWEIGHT")]
public:
property Decimal NetWeight {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[ItemDimensions Class](itemdimensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

