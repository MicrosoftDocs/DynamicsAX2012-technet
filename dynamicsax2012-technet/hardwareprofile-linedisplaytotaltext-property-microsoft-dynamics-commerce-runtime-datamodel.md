---
title: HardwareProfile.LineDisplayTotalText Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayTotalText Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayTotalText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaytotaltext(v=AX.60)
ms:contentKeyID: 62203661
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayTotalText
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayTotalText Property

Gets or sets the total text value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISPLAYTOTALTEXT")> _
<DataMemberAttribute> _
Public Property LineDisplayTotalText As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.LineDisplayTotalText

instance.LineDisplayTotalText = value
```

``` csharp
[ColumnAttribute("DISPLAYTOTALTEXT")]
[DataMemberAttribute]
public string LineDisplayTotalText { get; set; }
```

``` c++
[ColumnAttribute(L"DISPLAYTOTALTEXT")]
[DataMemberAttribute]
public:
property String^ LineDisplayTotalText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The total text.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

