---
title: ISaleLineItemV1.HasBeenRecalled Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: HasBeenRecalled Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.HasBeenRecalled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.hasbeenrecalled(v=AX.60)
ms:contentKeyID: 49832327
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.HasBeenRecalled
dev_langs:
- CSharp
- C++
- VB
---

# HasBeenRecalled Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Whether the item has been recalled or not.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property HasBeenRecalled As Boolean
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Boolean

value = instance.HasBeenRecalled

instance.HasBeenRecalled = value
```

``` csharp
bool HasBeenRecalled { get; set; }
```

``` c++
property bool HasBeenRecalled {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

