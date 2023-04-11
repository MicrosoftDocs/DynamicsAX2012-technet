---
title: IPosTransactionV2.LocalHourOfDay Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LocalHourOfDay Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.LocalHourOfDay
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv2.localhourofday(v=AX.60)
ms:contentKeyID: 49855186
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV2.LocalHourOfDay
dev_langs:
- CSharp
- C++
- VB
---

# LocalHourOfDay Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Local hour of day when transaction is created

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LocalHourOfDay As Integer
    Get
    Set
'Usage
Dim instance As IPosTransactionV2
Dim value As Integer

value = instance.LocalHourOfDay

instance.LocalHourOfDay = value
```

``` csharp
int LocalHourOfDay { get; set; }
```

``` c++
property int LocalHourOfDay {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[IPosTransactionV2 Interface](ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

