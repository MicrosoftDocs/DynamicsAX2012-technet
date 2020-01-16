---
title: ITaxableItem.EndDateTime Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EndDateTime Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.EndDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.enddatetime(v=AX.60)
ms:contentKeyID: 47129201
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.EndDateTime
dev_langs:
- CSharp
- C++
- VB
---

# EndDateTime Property

The end date and time of the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EndDateTime As DateTime
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As DateTime

value = instance.EndDateTime

instance.EndDateTime = value
```

``` csharp
DateTime EndDateTime { get; set; }
```

``` c++
property DateTime EndDateTime {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
The [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

