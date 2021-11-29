---
title: BarcodeMaskSegment.MaskId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaskId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.MaskId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemasksegment.maskid(v=AX.60)
ms:contentKeyID: 62212073
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.MaskId
dev_langs:
- CSharp
- C++
- VB
---

# MaskId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MASKID")> _
<DataMemberAttribute> _
Public Property MaskId As String
    Get
    Set
'Usage
Dim instance As BarcodeMaskSegment
Dim value As String

value = instance.MaskId

instance.MaskId = value
```

``` csharp
[ColumnAttribute("MASKID")]
[DataMemberAttribute]
public string MaskId { get; set; }
```

``` c++
[ColumnAttribute(L"MASKID")]
[DataMemberAttribute]
public:
property String^ MaskId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[BarcodeMaskSegment Class](barcodemasksegment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

