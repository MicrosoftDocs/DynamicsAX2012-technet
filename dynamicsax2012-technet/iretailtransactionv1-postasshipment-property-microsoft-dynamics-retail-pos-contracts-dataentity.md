---
title: IRetailTransactionV1.PostAsShipment Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PostAsShipment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.PostAsShipment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.postasshipment(v=AX.60)
ms:contentKeyID: 49843016
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.PostAsShipment
dev_langs:
- CSharp
- C++
- VB
---

# PostAsShipment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

If the sale should be posted as an invoice or a shipment. Only used if customer is selected.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PostAsShipment As Boolean
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Boolean

value = instance.PostAsShipment

instance.PostAsShipment = value
```

``` csharp
bool PostAsShipment { get; set; }
```

``` c++
property bool PostAsShipment {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

