---
title: ICustomerV1.Blocked Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Blocked Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.Blocked
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.blocked(v=AX.60)
ms:contentKeyID: 47128267
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.Blocked
dev_langs:
- CSharp
- C++
- VB
---

# Blocked Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the customer allowed to shop.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Blocked As BlockedEnum
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As BlockedEnum

value = instance.Blocked

instance.Blocked = value
```

``` csharp
BlockedEnum Blocked { get; set; }
```

``` c++
property BlockedEnum Blocked {
    BlockedEnum get ();
    void set (BlockedEnum value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.BlockedEnum](blockedenum-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.BlockedEnum](blockedenum-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md) value.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

