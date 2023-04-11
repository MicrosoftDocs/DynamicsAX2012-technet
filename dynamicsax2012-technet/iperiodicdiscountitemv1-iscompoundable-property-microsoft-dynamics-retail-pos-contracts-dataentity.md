---
title: IPeriodicDiscountItemV1.IsCompoundable Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IsCompoundable Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1.IsCompoundable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountitemv1.iscompoundable(v=AX.60)
ms:contentKeyID: 49844936
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1.IsCompoundable
dev_langs:
- CSharp
- C++
- VB
---

# IsCompoundable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Some discount methods (e.g. offer price) can not be compounded, even if they're designated to be

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IsCompoundable As Boolean
    Get
    Set
'Usage
Dim instance As IPeriodicDiscountItemV1
Dim value As Boolean

value = instance.IsCompoundable

instance.IsCompoundable = value
```

``` csharp
bool IsCompoundable { get; set; }
```

``` c++
property bool IsCompoundable {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IPeriodicDiscountItemV1 Interface](iperiodicdiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

