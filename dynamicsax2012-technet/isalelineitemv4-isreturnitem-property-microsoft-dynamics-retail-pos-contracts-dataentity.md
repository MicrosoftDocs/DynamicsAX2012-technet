---
title: ISaleLineItemV4.IsReturnItem Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IsReturnItem Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV4.IsReturnItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv4.isreturnitem(v=AX.60)
ms:contentKeyID: 62203707
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV4.IsReturnItem
dev_langs:
- CSharp
- C++
- VB
---

# IsReturnItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

True if the item is a returm item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IsReturnItem As Boolean
    Get
    Set
'Usage
Dim instance As ISaleLineItemV4
Dim value As Boolean

value = instance.IsReturnItem

instance.IsReturnItem = value
```

``` csharp
bool IsReturnItem { get; set; }
```

``` c++
property bool IsReturnItem {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV4 Interface](isalelineitemv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

