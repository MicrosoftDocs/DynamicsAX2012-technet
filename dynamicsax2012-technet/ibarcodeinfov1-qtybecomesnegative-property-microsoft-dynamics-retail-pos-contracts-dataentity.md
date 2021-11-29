---
title: IBarcodeInfoV1.QtyBecomesNegative Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: QtyBecomesNegative Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.QtyBecomesNegative
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.qtybecomesnegative(v=AX.60)
ms:contentKeyID: 47128203
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.QtyBecomesNegative
dev_langs:
- CSharp
- C++
- VB
---

# QtyBecomesNegative Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity to become negative. If set to true, the sign of the quantity is changed.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property QtyBecomesNegative As Boolean
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As Boolean

value = instance.QtyBecomesNegative

instance.QtyBecomesNegative = value
```

``` csharp
bool QtyBecomesNegative { get; set; }
```

``` c++
property bool QtyBecomesNegative {
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

