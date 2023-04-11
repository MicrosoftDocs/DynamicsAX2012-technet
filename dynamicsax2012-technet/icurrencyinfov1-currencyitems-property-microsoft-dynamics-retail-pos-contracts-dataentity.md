---
title: ICurrencyInfoV1.CurrencyItems Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CurrencyItems Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyInfoV1.CurrencyItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icurrencyinfov1.currencyitems(v=AX.60)
ms:contentKeyID: 47128283
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyInfoV1.CurrencyItems
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The currency details that are stored in a linked list.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CurrencyItems As ICurrencyItemInfo()
    Get
    Set
'Usage
Dim instance As ICurrencyInfoV1
Dim value As ICurrencyItemInfo()

value = instance.CurrencyItems

instance.CurrencyItems = value
```

``` csharp
ICurrencyItemInfo[] CurrencyItems { get; set; }
```

``` c++
property array<ICurrencyItemInfo^>^ CurrencyItems {
    array<ICurrencyItemInfo^>^ get ();
    void set (array<ICurrencyItemInfo^>^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyItemInfo](icurrencyiteminfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\[\]  
The [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyItemInfo](icurrencyiteminfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) value.  

## See Also

#### Reference

[ICurrencyInfoV1 Interface](icurrencyinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

