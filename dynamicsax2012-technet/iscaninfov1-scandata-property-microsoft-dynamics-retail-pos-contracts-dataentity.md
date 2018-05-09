---
title: IScanInfoV1.ScanData Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ScanData Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.ScanData
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iscaninfov1.scandata(v=AX.60)
ms:contentKeyID: 47128078
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.ScanData
dev_langs:
- CSharp
- C++
- VB
---

# ScanData Property

Gets or sets the barcode with prefix (F for EAN13 and so on).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ScanData As String
    Get
    Set
'Usage
Dim instance As IScanInfoV1
Dim value As String

value = instance.ScanData

instance.ScanData = value
```

``` csharp
string ScanData { get; set; }
```

``` c++
property String^ ScanData {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IScanInfoV1 Interface](iscaninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

