---
title: IPosCustomControlV1.TransactionChanged Method  (Microsoft.Dynamics.Retail.Pos.Contracts.UI)
TOCTitle: TransactionChanged Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.UI.IPosCustomControlV1.TransactionChanged(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.ui.iposcustomcontrolv1.transactionchanged(v=AX.60)
ms:contentKeyID: 49841041
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.UI.IPosCustomControlV1.TransactionChanged
dev_langs:
- CSharp
- C++
- VB
---

# TransactionChanged Method

Method is called when transactions changes.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.UI](microsoft-dynamics-retail-pos-contracts-ui-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub TransactionChanged ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IPosCustomControlV1
Dim transaction As IPosTransaction

instance.TransactionChanged(transaction)
```

``` csharp
void TransactionChanged(
    IPosTransaction transaction
)
```

``` c++
void TransactionChanged(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IPosCustomControlV1 Interface](iposcustomcontrolv1-interface-microsoft-dynamics-retail-pos-contracts-ui.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.UI Namespace](microsoft-dynamics-retail-pos-contracts-ui-namespace.md)

