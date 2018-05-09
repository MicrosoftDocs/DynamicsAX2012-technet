---
title: ISaleLineItemV1.ShouldBeManuallyRemoved Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ShouldBeManuallyRemoved Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.ShouldBeManuallyRemoved
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.shouldbemanuallyremoved(v=AX.60)
ms:contentKeyID: 49846699
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.ShouldBeManuallyRemoved
dev_langs:
- CSharp
- C++
- VB
---

# ShouldBeManuallyRemoved Property

Notifies the cahier that this item should be removed in order to continue

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ShouldBeManuallyRemoved As Boolean
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Boolean

value = instance.ShouldBeManuallyRemoved

instance.ShouldBeManuallyRemoved = value
```

``` csharp
bool ShouldBeManuallyRemoved { get; set; }
```

``` c++
property bool ShouldBeManuallyRemoved {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

