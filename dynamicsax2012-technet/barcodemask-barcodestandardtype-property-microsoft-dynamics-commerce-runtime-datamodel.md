---
title: BarcodeMask.BarcodeStandardType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BarcodeStandardType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask.BarcodeStandardType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemask.barcodestandardtype(v=AX.60)
ms:contentKeyID: 62207891
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask.BarcodeStandardType
dev_langs:
- CSharp
- C++
- VB
---

# BarcodeStandardType Property

Gets or sets the BarcodeStandardType.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SYMBOLOGY")> _
<DataMemberAttribute> _
Public Property BarcodeStandardType As Integer
    Get
    Set
'Usage
Dim instance As BarcodeMask
Dim value As Integer

value = instance.BarcodeStandardType

instance.BarcodeStandardType = value
```

``` csharp
[ColumnAttribute("SYMBOLOGY")]
[DataMemberAttribute]
public int BarcodeStandardType { get; set; }
```

``` c++
[ColumnAttribute(L"SYMBOLOGY")]
[DataMemberAttribute]
public:
property int BarcodeStandardType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[BarcodeMask Class](barcodemask-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

