---
title: ITaxItem.Price Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Price Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem.Price
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxitem.price(v=AX.60)
ms:contentKeyID: 47128858
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem.Price
dev_langs:
- CSharp
- C++
- VB
---

# Price Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the amount that is taxed.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Price As Decimal
    Get
    Set
'Usage
Dim instance As ITaxItem
Dim value As Decimal

value = instance.Price

instance.Price = value
```

``` csharp
decimal Price { get; set; }
```

``` c++
property Decimal Price {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxItem Interface](itaxitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

