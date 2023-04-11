---
title: IDirPartAddressRelationshipV1.RecId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RecId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDirPartAddressRelationshipV1.RecId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.idirpartaddressrelationshipv1.recid(v=AX.60)
ms:contentKeyID: 47128827
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDirPartAddressRelationshipV1.RecId
dev_langs:
- CSharp
- C++
- VB
---

# RecId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the record ID of the electronic address.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RecId As Long
    Get
    Set
'Usage
Dim instance As IDirPartAddressRelationshipV1
Dim value As Long

value = instance.RecId

instance.RecId = value
```

``` csharp
long RecId { get; set; }
```

``` c++
property long long RecId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)) value.  

## See Also

#### Reference

[IDirPartAddressRelationshipV1 Interface](idirpartaddressrelationshipv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

