---
title: HardwareProfile.DualDisplayImageRotatorPath Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DualDisplayImageRotatorPath Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayImageRotatorPath
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.dualdisplayimagerotatorpath(v=AX.60)
ms:contentKeyID: 62212917
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayImageRotatorPath
dev_langs:
- CSharp
- C++
- VB
---

# DualDisplayImageRotatorPath Property

Gets or sets the dual display image rotator path.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DUALDISPLAYIMAGEPATH")> _
<DataMemberAttribute> _
Public Property DualDisplayImageRotatorPath As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.DualDisplayImageRotatorPath

instance.DualDisplayImageRotatorPath = value
```

``` csharp
[ColumnAttribute("DUALDISPLAYIMAGEPATH")]
[DataMemberAttribute]
public string DualDisplayImageRotatorPath { get; set; }
```

``` c++
[ColumnAttribute(L"DUALDISPLAYIMAGEPATH")]
[DataMemberAttribute]
public:
property String^ DualDisplayImageRotatorPath {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The image path.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

