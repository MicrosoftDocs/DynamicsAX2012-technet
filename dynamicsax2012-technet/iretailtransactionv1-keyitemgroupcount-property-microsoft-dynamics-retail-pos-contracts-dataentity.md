---
title: IRetailTransactionV1.KeyItemGroupCount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: KeyItemGroupCount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.KeyItemGroupCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.keyitemgroupcount(v=AX.60)
ms:contentKeyID: 49855612
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.KeyItemGroupCount
dev_langs:
- CSharp
- C++
- VB
---

# KeyItemGroupCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The number of items that where sold on an item group.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property KeyItemGroupCount As Integer
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Integer

value = instance.KeyItemGroupCount

instance.KeyItemGroupCount = value
```

``` csharp
int KeyItemGroupCount { get; set; }
```

``` c++
property int KeyItemGroupCount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

