---
title: IPeriodicDiscountV1.HasItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: HasItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountV1.HasItem(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountv1.hasitem(v=AX.60)
ms:contentKeyID: 49842401
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountV1.HasItem
dev_langs:
- CSharp
- C++
- VB
---

# HasItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns true when the indicated item/variant discount rows have already been added to the cache (whether with a discount or no discount). This will prevent unneeded trips to the DB for subsequent calls.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function HasItem ( _
    productId As Long, _
    distinctProductVariantId As Long _
) As Boolean
'Usage
Dim instance As IPeriodicDiscountV1
Dim productId As Long
Dim distinctProductVariantId As Long
Dim returnValue As Boolean

returnValue = instance.HasItem(productId, _
    distinctProductVariantId)
```

``` csharp
bool HasItem(
    long productId,
    long distinctProductVariantId
)
```

``` c++
bool HasItem(
    long long productId, 
    long long distinctProductVariantId
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - distinctProductVariantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IPeriodicDiscountV1 Interface](iperiodicdiscountv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

