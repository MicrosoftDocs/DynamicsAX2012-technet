---
title: ICustomerOrderTransactionV2.WarehouseId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: WarehouseId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.WarehouseId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerordertransactionv2.warehouseid(v=AX.60)
ms:contentKeyID: 49822309
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.WarehouseId
dev_langs:
- CSharp
- C++
- VB
---

# WarehouseId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Warehouse ID

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property WarehouseId As String
    Get
    Set
'Usage
Dim instance As ICustomerOrderTransactionV2
Dim value As String

value = instance.WarehouseId

instance.WarehouseId = value
```

``` csharp
string WarehouseId { get; set; }
```

``` c++
property String^ WarehouseId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerOrderTransactionV2 Interface](icustomerordertransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

