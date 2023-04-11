---
title: IDiscountItemV1.BeginDateTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BeginDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItemV1.BeginDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.idiscountitemv1.begindatetime(v=AX.60)
ms:contentKeyID: 49840427
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItemV1.BeginDateTime
dev_langs:
- CSharp
- C++
- VB
---

# BeginDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The start date and time of the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BeginDateTime As DateTime
    Get
    Set
'Usage
Dim instance As IDiscountItemV1
Dim value As DateTime

value = instance.BeginDateTime

instance.BeginDateTime = value
```

``` csharp
DateTime BeginDateTime { get; set; }
```

``` c++
property DateTime BeginDateTime {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[IDiscountItemV1 Interface](idiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

