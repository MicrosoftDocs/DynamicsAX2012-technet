---
title: BarcodeMaskSegment.Decimals Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Decimals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.Decimals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemasksegment.decimals(v=AX.60)
ms:contentKeyID: 62211778
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskSegment.Decimals
dev_langs:
- CSharp
- C++
- VB
---

# Decimals Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DECIMALS")> _
Public Property Decimals As Integer
    Get
    Set
'Usage
Dim instance As BarcodeMaskSegment
Dim value As Integer

value = instance.Decimals

instance.Decimals = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DECIMALS")]
public int Decimals { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DECIMALS")]
public:
property int Decimals {
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

