---
title: IRetailTransactionV4.LoyaltyItem Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyItem Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV4.LoyaltyItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv4.loyaltyitem(v=AX.60)
ms:contentKeyID: 62202746
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV4.LoyaltyItem
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LoyaltyItem As ILoyaltyItem
    Get
    Set
'Usage
Dim instance As IRetailTransactionV4
Dim value As ILoyaltyItem

value = instance.LoyaltyItem

instance.LoyaltyItem = value
```

``` csharp
ILoyaltyItem LoyaltyItem { get; set; }
```

``` c++
property ILoyaltyItem^ LoyaltyItem {
    ILoyaltyItem^ get ();
    void set (ILoyaltyItem^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItem](iloyaltyitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [ILoyaltyItem](iloyaltyitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[IRetailTransactionV4 Interface](iretailtransactionv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

