---
title: HardwareProfile.MsrMake Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MsrMake Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MSRMake
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.msrmake(v=AX.60)
ms:contentKeyID: 62214092
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MsrMake
dev_langs:
- CSharp
- C++
- VB
---

# MsrMake Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MSRMAKE")> _
<DataMemberAttribute> _
Public Property MsrMake As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.MsrMake

instance.MsrMake = value
```

``` csharp
[ColumnAttribute("MSRMAKE")]
[DataMemberAttribute]
public string MsrMake { get; set; }
```

``` c++
[ColumnAttribute(L"MSRMAKE")]
[DataMemberAttribute]
public:
property String^ MsrMake {
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

