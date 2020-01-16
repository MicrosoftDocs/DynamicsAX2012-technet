---
title: HardwareProfile.MsrEndTrack1 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MsrEndTrack1 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MSREndTrack1
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.msrendtrack1(v=AX.60)
ms:contentKeyID: 62205125
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MsrEndTrack1
dev_langs:
- CSharp
- C++
- VB
---

# MsrEndTrack1 Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ENDTRACK1")> _
<DataMemberAttribute> _
Public Property MsrEndTrack1 As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.MsrEndTrack1

instance.MsrEndTrack1 = value
```

``` csharp
[ColumnAttribute("ENDTRACK1")]
[DataMemberAttribute]
public string MsrEndTrack1 { get; set; }
```

``` c++
[ColumnAttribute(L"ENDTRACK1")]
[DataMemberAttribute]
public:
property String^ MsrEndTrack1 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

