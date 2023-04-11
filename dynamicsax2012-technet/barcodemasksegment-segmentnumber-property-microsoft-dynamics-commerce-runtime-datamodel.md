---
title: BarcodeMaskSegment.SegmentNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SegmentNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.SegmentNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemasksegment.segmentnumber(v=AX.60)
ms:contentKeyID: 62211538
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.SegmentNumber
dev_langs:
- CSharp
- C++
- VB
---

# SegmentNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SEGMENTNUM")> _
<DataMemberAttribute> _
Public Property SegmentNumber As Integer
    Get
    Set
'Usage
Dim instance As BarcodeMaskSegment
Dim value As Integer

value = instance.SegmentNumber

instance.SegmentNumber = value
```

``` csharp
[ColumnAttribute("SEGMENTNUM")]
[DataMemberAttribute]
public int SegmentNumber { get; set; }
```

``` c++
[ColumnAttribute(L"SEGMENTNUM")]
[DataMemberAttribute]
public:
property int SegmentNumber {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[BarcodeMaskSegment Class](barcodemasksegment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

