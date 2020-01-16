---
title: HardwareProfile.ProfileDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProfileDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ProfileDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.profiledescription(v=AX.60)
ms:contentKeyID: 62207771
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ProfileDescription
dev_langs:
- CSharp
- C++
- VB
---

# ProfileDescription Property

Gets or sets the hardware profile description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NAME")> _
<DataMemberAttribute> _
Public Property ProfileDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.ProfileDescription

instance.ProfileDescription = value
```

``` csharp
[ColumnAttribute("NAME")]
[DataMemberAttribute]
public string ProfileDescription { get; set; }
```

``` c++
[ColumnAttribute(L"NAME")]
[DataMemberAttribute]
public:
property String^ ProfileDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The hardware profile description string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

