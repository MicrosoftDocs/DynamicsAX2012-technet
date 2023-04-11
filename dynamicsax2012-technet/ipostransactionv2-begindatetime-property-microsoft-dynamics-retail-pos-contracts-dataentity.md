---
title: IPosTransactionV2.BeginDateTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BeginDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.BeginDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv2.begindatetime(v=AX.60)
ms:contentKeyID: 49850731
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.BeginDateTime
dev_langs:
- CSharp
- C++
- VB
---

# BeginDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Set start date and time of the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
WriteOnly Property BeginDateTime As DateTime
    Set
'Usage
Dim instance As IPosTransactionV2
Dim value As DateTime

instance.BeginDateTime = value
```

``` csharp
DateTime BeginDateTime { set; }
```

``` c++
property DateTime BeginDateTime {
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[IPosTransactionV2 Interface](ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

