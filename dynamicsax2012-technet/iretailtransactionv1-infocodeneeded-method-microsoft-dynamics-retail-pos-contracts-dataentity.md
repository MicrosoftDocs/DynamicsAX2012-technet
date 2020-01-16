---
title: IRetailTransactionV1.InfoCodeNeeded Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InfoCodeNeeded Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.InfoCodeNeeded(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.infocodeneeded(v=AX.60)
ms:contentKeyID: 49841432
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.InfoCodeNeeded
dev_langs:
- CSharp
- C++
- VB
---

# InfoCodeNeeded Method

Looks through existing infocodes and check if the infocode already exists on the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function InfoCodeNeeded ( _
    infoCodeId As String _
) As Boolean
'Usage
Dim instance As IRetailTransactionV1
Dim infoCodeId As String
Dim returnValue As Boolean

returnValue = instance.InfoCodeNeeded(infoCodeId)
```

``` csharp
bool InfoCodeNeeded(
    string infoCodeId
)
```

``` c++
bool InfoCodeNeeded(
    String^ infoCodeId
)
```

#### Parameters

  - infoCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

