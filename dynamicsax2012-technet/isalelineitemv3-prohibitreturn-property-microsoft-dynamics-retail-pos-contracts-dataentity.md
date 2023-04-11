---
title: ISaleLineItemV3.ProhibitReturn Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ProhibitReturn Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV3.ProhibitReturn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv3.prohibitreturn(v=AX.60)
ms:contentKeyID: 62205184
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV3.ProhibitReturn
dev_langs:
- CSharp
- C++
- VB
---

# ProhibitReturn Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Is true if the item is blocked from being returned on the POS system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ProhibitReturn As Boolean
    Get
    Set
'Usage
Dim instance As ISaleLineItemV3
Dim value As Boolean

value = instance.ProhibitReturn

instance.ProhibitReturn = value
```

``` csharp
bool ProhibitReturn { get; set; }
```

``` c++
property bool ProhibitReturn {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV3 Interface](isalelineitemv3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

