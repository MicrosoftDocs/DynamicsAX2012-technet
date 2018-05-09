---
title: ITaxItem.Amount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Amount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem.Amount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxitem.amount(v=AX.60)
ms:contentKeyID: 47128863
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem.Amount
dev_langs:
- CSharp
- C++
- VB
---

# Amount Property

Gets or sets the tax amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Amount As Decimal
    Get
    Set
'Usage
Dim instance As ITaxItem
Dim value As Decimal

value = instance.Amount

instance.Amount = value
```

``` csharp
decimal Amount { get; set; }
```

``` c++
property Decimal Amount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxItem Interface](itaxitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

