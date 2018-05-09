---
title: BarcodeMaskSegment.MaskType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaskType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.MaskType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemasksegment.masktype(v=AX.60)
ms:contentKeyID: 62211942
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.MaskType
dev_langs:
- CSharp
- C++
- VB
---

# MaskType Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TYPE")> _
Public Property MaskType As Integer
    Get
    Set
'Usage
Dim instance As BarcodeMaskSegment
Dim value As Integer

value = instance.MaskType

instance.MaskType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TYPE")]
public int MaskType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TYPE")]
public:
property int MaskType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[BarcodeMaskSegment Class](barcodemasksegment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

