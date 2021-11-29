---
title: IBarcodeInfoV1.Blocked Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Blocked Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.Blocked
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.blocked(v=AX.60)
ms:contentKeyID: 47129048
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.Blocked
dev_langs:
- CSharp
- C++
- VB
---

# Blocked Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the blocked barcode. Returns true if the barcode should be blocked, otherwise it returns false.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Blocked As Boolean
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As Boolean

value = instance.Blocked

instance.Blocked = value
```

``` csharp
bool Blocked { get; set; }
```

``` c++
property bool Blocked {
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

