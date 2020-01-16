---
title: HardwareProfile.EftServerPort Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftServerPort Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTServerPort
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftserverport(v=AX.60)
ms:contentKeyID: 62209170
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftServerPort
dev_langs:
- CSharp
- C++
- VB
---

# EftServerPort Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EFTSERVERPORT")> _
Public Property EftServerPort As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.EftServerPort

instance.EftServerPort = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EFTSERVERPORT")]
public string EftServerPort { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EFTSERVERPORT")]
public:
property String^ EftServerPort {
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

