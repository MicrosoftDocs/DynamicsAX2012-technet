---
title: IPosTransactionV1.StatementMethod Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: StatementMethod Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.StatementMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.statementmethod(v=AX.60)
ms:contentKeyID: 47128832
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.StatementMethod
dev_langs:
- CSharp
- C++
- VB
---

# StatementMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the way a statement is done for the store (staff, terminal, or total).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property StatementMethod As Integer
    Get
'Usage
Dim instance As IPosTransactionV1
Dim value As Integer

value = instance.StatementMethod
```

``` csharp
int StatementMethod { get; }
```

``` c++
property int StatementMethod {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

