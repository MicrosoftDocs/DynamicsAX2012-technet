---
title: ILineItemV1.LineId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LineId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineItemV1.LineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ilineitemv1.lineid(v=AX.60)
ms:contentKeyID: 49845394
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineItemV1.LineId
dev_langs:
- CSharp
- C++
- VB
---

# LineId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The unique id of each line in the transaction

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property LineId As Integer
    Get
'Usage
Dim instance As ILineItemV1
Dim value As Integer

value = instance.LineId
```

``` csharp
int LineId { get; }
```

``` c++
property int LineId {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ILineItemV1 Interface](ilineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

