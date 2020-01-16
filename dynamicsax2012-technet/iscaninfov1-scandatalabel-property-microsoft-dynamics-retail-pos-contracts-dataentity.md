---
title: IScanInfoV1.ScanDataLabel Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ScanDataLabel Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.ScanDataLabel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iscaninfov1.scandatalabel(v=AX.60)
ms:contentKeyID: 47128816
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.ScanDataLabel
dev_langs:
- CSharp
- C++
- VB
---

# ScanDataLabel Property

Gets or sets the striped barcode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ScanDataLabel As String
    Get
    Set
'Usage
Dim instance As IScanInfoV1
Dim value As String

value = instance.ScanDataLabel

instance.ScanDataLabel = value
```

``` csharp
string ScanDataLabel { get; set; }
```

``` c++
property String^ ScanDataLabel {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IScanInfoV1 Interface](iscaninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

