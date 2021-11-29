---
title: IPeriodV1.Add Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Add Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodV1.Add(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodv1.add(v=AX.60)
ms:contentKeyID: 49823518
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodV1.Add
dev_langs:
- CSharp
- C++
- VB
---

# Add Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Add's a new period if not found in memorytable

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub Add ( _
    periodId As String, _
    valid As Boolean _
)
'Usage
Dim instance As IPeriodV1
Dim periodId As String
Dim valid As Boolean

instance.Add(periodId, valid)
```

``` csharp
void Add(
    string periodId,
    bool valid
)
```

``` c++
void Add(
    String^ periodId, 
    bool valid
)
```

#### Parameters

  - periodId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - valid  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IPeriodV1 Interface](iperiodv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

