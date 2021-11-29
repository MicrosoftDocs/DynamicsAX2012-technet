---
title: ICustomerV1.PartyId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PartyId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.PartyId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.partyid(v=AX.60)
ms:contentKeyID: 47128822
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.PartyId
dev_langs:
- CSharp
- C++
- VB
---

# PartyId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The party ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PartyId As Long
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As Long

value = instance.PartyId

instance.PartyId = value
```

``` csharp
long PartyId { get; set; }
```

``` c++
property long long PartyId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)) value.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

