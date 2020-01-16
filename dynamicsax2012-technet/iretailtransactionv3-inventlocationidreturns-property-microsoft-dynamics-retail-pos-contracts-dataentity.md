---
title: IRetailTransactionV3.InventLocationIdReturns Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InventLocationIdReturns Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV3.InventLocationIdReturns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv3.inventlocationidreturns(v=AX.60)
ms:contentKeyID: 62204702
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV3.InventLocationIdReturns
dev_langs:
- CSharp
- C++
- VB
---

# InventLocationIdReturns Property

Warehouse ID for returns

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InventLocationIdReturns As String
    Get
    Set
'Usage
Dim instance As IRetailTransactionV3
Dim value As String

value = instance.InventLocationIdReturns

instance.InventLocationIdReturns = value
```

``` csharp
string InventLocationIdReturns { get; set; }
```

``` c++
property String^ InventLocationIdReturns {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV3 Interface](iretailtransactionv3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

