---
title: IItemV1.PurchaseModel Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PurchaseModel Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PurchaseModel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.purchasemodel(v=AX.60)
ms:contentKeyID: 49853070
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PurchaseModel
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseModel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the purchase model.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PurchaseModel As Integer
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Integer

value = instance.PurchaseModel

instance.PurchaseModel = value
```

``` csharp
int PurchaseModel { get; set; }
```

``` c++
property int PurchaseModel {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The purchase model.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

