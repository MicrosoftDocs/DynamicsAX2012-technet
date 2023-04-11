---
title: Barcode.MaskType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaskType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.MaskType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.masktype(v=AX.60)
ms:contentKeyID: 62202923
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.MaskType
dev_langs:
- CSharp
- C++
- VB
---

# MaskType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property MaskType As BarcodeMaskType
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As BarcodeMaskType

value = instance.MaskType

instance.MaskType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public BarcodeMaskType MaskType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property BarcodeMaskType MaskType {
    BarcodeMaskType get ();
    void set (BarcodeMaskType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMaskType](barcodemasktype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

