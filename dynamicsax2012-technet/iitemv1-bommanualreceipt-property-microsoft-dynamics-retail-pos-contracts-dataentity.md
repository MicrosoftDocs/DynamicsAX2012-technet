---
title: IItemV1.BomManualReceipt Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BomManualReceipt Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.BomManualReceipt
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.bommanualreceipt(v=AX.60)
ms:contentKeyID: 49824789
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.BomManualReceipt
dev_langs:
- CSharp
- C++
- VB
---

# BomManualReceipt Property

Gets or sets the bom manual receipt.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BomManualReceipt As Integer
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Integer

value = instance.BomManualReceipt

instance.BomManualReceipt = value
```

``` csharp
int BomManualReceipt { get; set; }
```

``` c++
property int BomManualReceipt {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The bom manual receipt.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

