---
title: ITenderV2.SigCapEnabled Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SigCapEnabled Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV2.SigCapEnabled
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderv2.sigcapenabled(v=AX.60)
ms:contentKeyID: 49855212
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV2.SigCapEnabled
dev_langs:
- CSharp
- C++
- VB
---

# SigCapEnabled Property

Gets or sets flag for signature capture enabled setting.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SigCapEnabled As Boolean
    Get
    Set
'Usage
Dim instance As ITenderV2
Dim value As Boolean

value = instance.SigCapEnabled

instance.SigCapEnabled = value
```

``` csharp
bool SigCapEnabled { get; set; }
```

``` c++
property bool SigCapEnabled {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ITenderV2 Interface](itenderv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

