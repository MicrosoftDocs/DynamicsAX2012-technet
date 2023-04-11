---
title: IBarcodeInfoV1.NoDiscountAllowed Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: NoDiscountAllowed Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.NoDiscountAllowed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.nodiscountallowed(v=AX.60)
ms:contentKeyID: 47128876
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.NoDiscountAllowed
dev_langs:
- CSharp
- C++
- VB
---

# NoDiscountAllowed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether no discount is allowed for an item. If set to true, discount is not allowed for the item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property NoDiscountAllowed As Boolean
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As Boolean

value = instance.NoDiscountAllowed

instance.NoDiscountAllowed = value
```

``` csharp
bool NoDiscountAllowed { get; set; }
```

``` c++
property bool NoDiscountAllowed {
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

