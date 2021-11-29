---
title: ITaxableItem.Add Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Add Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.Add(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.add(v=AX.60)
ms:contentKeyID: 47128272
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.Add
dev_langs:
- CSharp
- C++
- VB
---

# Add Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds the specified tax line item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub Add ( _
    taxLineItem As ITaxItem _
)
'Usage
Dim instance As ITaxableItem
Dim taxLineItem As ITaxItem

instance.Add(taxLineItem)
```

``` csharp
void Add(
    ITaxItem taxLineItem
)
```

``` c++
void Add(
    ITaxItem^ taxLineItem
)
```

#### Parameters

  - taxLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem](itaxitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

