---
title: IRetailTransactionV2.RequestedDeliveryDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RequestedDeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.RequestedDeliveryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv2.requesteddeliverydate(v=AX.60)
ms:contentKeyID: 49827281
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV2.RequestedDeliveryDate
dev_langs:
- CSharp
- C++
- VB
---

# RequestedDeliveryDate Property

Requested Delivery date for the order

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RequestedDeliveryDate As DateTime
    Get
    Set
'Usage
Dim instance As IRetailTransactionV2
Dim value As DateTime

value = instance.RequestedDeliveryDate

instance.RequestedDeliveryDate = value
```

``` csharp
DateTime RequestedDeliveryDate { get; set; }
```

``` c++
property DateTime RequestedDeliveryDate {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV2 Interface](iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

