---
title: IPeriodicDiscountV1.Get Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountV1.Get(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountv1.get(v=AX.60)
ms:contentKeyID: 49826721
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountV1.Get
dev_langs:
- CSharp
- C++
- VB
---

# Get Method

Retrieves the applicable discount lines for the item/variant.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Get ( _
    productId As Long, _
    distinctProductVariantId As Long _
) As DataTable
'Usage
Dim instance As IPeriodicDiscountV1
Dim productId As Long
Dim distinctProductVariantId As Long
Dim returnValue As DataTable

returnValue = instance.Get(productId, _
    distinctProductVariantId)
```

``` csharp
DataTable Get(
    long productId,
    long distinctProductVariantId
)
```

``` c++
DataTable^ Get(
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

Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

## See Also

#### Reference

[IPeriodicDiscountV1 Interface](iperiodicdiscountv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

