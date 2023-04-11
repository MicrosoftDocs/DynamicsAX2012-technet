---
title: HardwareProfile.LineDisplayClosedLine1 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayClosedLine1 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayClosedLine1
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplayclosedline1(v=AX.60)
ms:contentKeyID: 62207591
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayClosedLine1
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayClosedLine1 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the first display closed line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISPLAYCLOSEDLINE1")> _
<DataMemberAttribute> _
Public Property LineDisplayClosedLine1 As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.LineDisplayClosedLine1

instance.LineDisplayClosedLine1 = value
```

``` csharp
[ColumnAttribute("DISPLAYCLOSEDLINE1")]
[DataMemberAttribute]
public string LineDisplayClosedLine1 { get; set; }
```

``` c++
[ColumnAttribute(L"DISPLAYCLOSEDLINE1")]
[DataMemberAttribute]
public:
property String^ LineDisplayClosedLine1 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The text value.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

