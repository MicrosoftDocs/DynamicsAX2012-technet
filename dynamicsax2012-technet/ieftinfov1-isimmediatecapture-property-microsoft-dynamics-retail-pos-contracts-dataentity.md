---
title: IEFTInfoV1.IsImmediateCapture Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IsImmediateCapture Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.IsImmediateCapture
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.isimmediatecapture(v=AX.60)
ms:contentKeyID: 47129183
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.IsImmediateCapture
dev_langs:
- CSharp
- C++
- VB
---

# IsImmediateCapture Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get or sets whether the transaction is using immediate capture. The default is false for AuthOnly and CaptureOnly. true means we used auth and capture in one operation. This is a special case currently only supported by FDC EMP for debit cards.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IsImmediateCapture As Boolean
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As Boolean

value = instance.IsImmediateCapture

instance.IsImmediateCapture = value
```

``` csharp
bool IsImmediateCapture { get; set; }
```

``` c++
property bool IsImmediateCapture {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

