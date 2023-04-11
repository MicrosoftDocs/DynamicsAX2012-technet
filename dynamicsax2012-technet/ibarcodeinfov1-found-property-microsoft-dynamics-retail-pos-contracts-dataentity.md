---
title: IBarcodeInfoV1.Found Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Found Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.Found
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.found(v=AX.60)
ms:contentKeyID: 47128044
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.Found
dev_langs:
- CSharp
- C++
- VB
---

# Found Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the found. Returns true if the barcode was found; otherwise it returns false.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Found As Boolean
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As Boolean

value = instance.Found

instance.Found = value
```

``` csharp
bool Found { get; set; }
```

``` c++
property bool Found {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

