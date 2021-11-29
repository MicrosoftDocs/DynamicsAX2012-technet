---
title: IDialogV1.InventoryLookup Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: InventoryLookup Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.InventoryLookup(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.inventorylookup(v=AX.60)
ms:contentKeyID: 47344114
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.InventoryLookup
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLookup Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Displays the inventory search through transaction service. This dialog show quantity on hand in multiple stores.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function InventoryLookup ( _
    posTransaction As IPosTransaction _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim posTransaction As IPosTransaction
Dim returnValue As DialogResult

returnValue = instance.InventoryLookup(posTransaction)
```

``` csharp
DialogResult InventoryLookup(
    IPosTransaction posTransaction
)
```

``` c++
DialogResult InventoryLookup(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

