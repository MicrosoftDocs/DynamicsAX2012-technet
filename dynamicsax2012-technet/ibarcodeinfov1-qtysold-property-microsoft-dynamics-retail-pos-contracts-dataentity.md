---
title: IBarcodeInfoV1.QtySold Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: QtySold Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.QtySold
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.qtysold(v=AX.60)
ms:contentKeyID: 47128878
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.QtySold
dev_langs:
- CSharp
- C++
- VB
---

# QtySold Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity sold. Specifies how many of the found item is sold.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property QtySold As Decimal
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As Decimal

value = instance.QtySold

instance.QtySold = value
```

``` csharp
decimal QtySold { get; set; }
```

``` c++
property Decimal QtySold {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

