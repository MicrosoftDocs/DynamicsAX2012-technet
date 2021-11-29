---
title: BarcodeMask.Mask Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Mask Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask.Mask
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemask.mask(v=AX.60)
ms:contentKeyID: 62211710
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask.Mask
dev_langs:
- CSharp
- C++
- VB
---

# Mask Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Mask.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MASK")> _
<DataMemberAttribute> _
Public Property Mask As String
    Get
    Set
'Usage
Dim instance As BarcodeMask
Dim value As String

value = instance.Mask

instance.Mask = value
```

``` csharp
[ColumnAttribute("MASK")]
[DataMemberAttribute]
public string Mask { get; set; }
```

``` c++
[ColumnAttribute(L"MASK")]
[DataMemberAttribute]
public:
property String^ Mask {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[BarcodeMask Class](barcodemask-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

