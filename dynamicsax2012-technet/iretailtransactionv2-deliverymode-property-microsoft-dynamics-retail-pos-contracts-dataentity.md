---
title: IRetailTransactionV2.DeliveryMode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DeliveryMode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.DeliveryMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv2.deliverymode(v=AX.60)
ms:contentKeyID: 49848673
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.DeliveryMode
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryMode Property

Delivery mode for the order

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DeliveryMode As IDeliveryMode
    Get
    Set
'Usage
Dim instance As IRetailTransactionV2
Dim value As IDeliveryMode

value = instance.DeliveryMode

instance.DeliveryMode = value
```

``` csharp
IDeliveryMode DeliveryMode { get; set; }
```

``` c++
property IDeliveryMode^ DeliveryMode {
    IDeliveryMode^ get ();
    void set (IDeliveryMode^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDeliveryMode](ideliverymode-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [IDeliveryMode](ideliverymode-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[IRetailTransactionV2 Interface](iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

