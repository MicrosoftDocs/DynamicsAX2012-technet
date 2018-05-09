---
title: IPosTransactionV1.CreatedOnTerminalId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CreatedOnTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.CreatedOnTerminalId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.createdonterminalid(v=AX.60)
ms:contentKeyID: 47128818
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.CreatedOnTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# CreatedOnTerminalId Property

Gets the original terminal that the transaction was created on, if the transaction was transferred from another terminal.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CreatedOnTerminalId As String
    Get
'Usage
Dim instance As IPosTransactionV1
Dim value As String

value = instance.CreatedOnTerminalId
```

``` csharp
string CreatedOnTerminalId { get; }
```

``` c++
property String^ CreatedOnTerminalId {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

