---
title: IScanInfoV1.ScanDataType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ScanDataType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.ScanDataType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iscaninfov1.scandatatype(v=AX.60)
ms:contentKeyID: 47128696
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.ScanDataType
dev_langs:
- CSharp
- C++
- VB
---

# ScanDataType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of barcode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ScanDataType As Integer
    Get
    Set
'Usage
Dim instance As IScanInfoV1
Dim value As Integer

value = instance.ScanDataType

instance.ScanDataType = value
```

``` csharp
int ScanDataType { get; set; }
```

``` c++
property int ScanDataType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)) value.  

## See Also

#### Reference

[IScanInfoV1 Interface](iscaninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

