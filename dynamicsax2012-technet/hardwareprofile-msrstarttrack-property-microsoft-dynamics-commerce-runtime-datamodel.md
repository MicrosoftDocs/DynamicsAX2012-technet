---
title: HardwareProfile.MsrStartTrack Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MsrStartTrack Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MSRStartTrack
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.msrstarttrack(v=AX.60)
ms:contentKeyID: 62213067
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MsrStartTrack
dev_langs:
- CSharp
- C++
- VB
---

# MsrStartTrack Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STARTTRACK1")> _
<DataMemberAttribute> _
Public Property MsrStartTrack As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.MsrStartTrack

instance.MsrStartTrack = value
```

``` csharp
[ColumnAttribute("STARTTRACK1")]
[DataMemberAttribute]
public string MsrStartTrack { get; set; }
```

``` c++
[ColumnAttribute(L"STARTTRACK1")]
[DataMemberAttribute]
public:
property String^ MsrStartTrack {
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

