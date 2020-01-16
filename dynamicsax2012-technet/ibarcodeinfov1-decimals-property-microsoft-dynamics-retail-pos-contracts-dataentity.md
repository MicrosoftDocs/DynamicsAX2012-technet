---
title: IBarcodeInfoV1.Decimals Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Decimals Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.Decimals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.decimals(v=AX.60)
ms:contentKeyID: 47129306
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.Decimals
dev_langs:
- CSharp
- C++
- VB
---

# Decimals Property

Gets or sets decimals.

The number of decimals as defined for the barcode, if the barcode stores either a price or quantity.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Decimals As Integer
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As Integer

value = instance.Decimals

instance.Decimals = value
```

``` csharp
int Decimals { get; set; }
```

``` c++
property int Decimals {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

