---
title: BarcodeMaskSegment.Length Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Length Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.Length
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemasksegment.length(v=AX.60)
ms:contentKeyID: 62210030
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.Length
dev_langs:
- CSharp
- C++
- VB
---

# Length Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LENGTH")> _
<DataMemberAttribute> _
Public Property Length As Integer
    Get
    Set
'Usage
Dim instance As BarcodeMaskSegment
Dim value As Integer

value = instance.Length

instance.Length = value
```

``` csharp
[ColumnAttribute("LENGTH")]
[DataMemberAttribute]
public int Length { get; set; }
```

``` c++
[ColumnAttribute(L"LENGTH")]
[DataMemberAttribute]
public:
property int Length {
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

