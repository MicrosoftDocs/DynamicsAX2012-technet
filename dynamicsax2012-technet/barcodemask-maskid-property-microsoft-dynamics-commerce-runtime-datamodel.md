---
title: BarcodeMask.MaskId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaskId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask.MaskId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcodemask.maskid(v=AX.60)
ms:contentKeyID: 62203630
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.BarcodeMask.MaskId
dev_langs:
- CSharp
- C++
- VB
---

# MaskId Property

Gets or sets the Mask identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MASKID")> _
Public Property MaskId As String
    Get
    Set
'Usage
Dim instance As BarcodeMask
Dim value As String

value = instance.MaskId

instance.MaskId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MASKID")]
public string MaskId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MASKID")]
public:
property String^ MaskId {
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

