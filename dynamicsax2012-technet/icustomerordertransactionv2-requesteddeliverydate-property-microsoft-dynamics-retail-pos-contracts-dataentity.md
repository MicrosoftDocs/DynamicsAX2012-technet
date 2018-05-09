---
title: ICustomerOrderTransactionV2.RequestedDeliveryDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RequestedDeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.RequestedDeliveryDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerordertransactionv2.requesteddeliverydate(v=AX.60)
ms:contentKeyID: 49846667
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.RequestedDeliveryDate
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
Dim instance As ICustomerOrderTransactionV2
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

Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerOrderTransactionV2 Interface](icustomerordertransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

