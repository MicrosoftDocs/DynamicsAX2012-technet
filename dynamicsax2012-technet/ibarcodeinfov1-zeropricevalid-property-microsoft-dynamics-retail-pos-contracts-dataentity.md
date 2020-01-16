---
title: IBarcodeInfoV1.ZeroPriceValid Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ZeroPriceValid Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.ZeroPriceValid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.zeropricevalid(v=AX.60)
ms:contentKeyID: 47128664
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.ZeroPriceValid
dev_langs:
- CSharp
- C++
- VB
---

# ZeroPriceValid Property

Gets or sets the zero price. If set to true, zero price is allowed for the item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ZeroPriceValid As Boolean
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As Boolean

value = instance.ZeroPriceValid

instance.ZeroPriceValid = value
```

``` csharp
bool ZeroPriceValid { get; set; }
```

``` c++
property bool ZeroPriceValid {
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

