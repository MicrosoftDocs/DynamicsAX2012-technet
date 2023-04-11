---
title: ISaleLineItemV1.DateToBeBlocked Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DateToBeBlocked Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.DateToBeBlocked
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.datetobeblocked(v=AX.60)
ms:contentKeyID: 49831035
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.DateToBeBlocked
dev_langs:
- CSharp
- C++
- VB
---

# DateToBeBlocked Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The date when the blocking becomes active

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DateToBeBlocked As DateTime
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As DateTime

value = instance.DateToBeBlocked

instance.DateToBeBlocked = value
```

``` csharp
DateTime DateToBeBlocked { get; set; }
```

``` c++
property DateTime DateToBeBlocked {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

