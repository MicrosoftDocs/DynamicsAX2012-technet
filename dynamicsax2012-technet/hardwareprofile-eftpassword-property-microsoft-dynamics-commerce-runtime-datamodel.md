---
title: HardwareProfile.EftPassword Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftpassword(v=AX.60)
ms:contentKeyID: 62211573
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftPassword
dev_langs:
- CSharp
- C++
- VB
---

# EftPassword Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EFTPASSWORD")> _
<DataMemberAttribute> _
Public Property EftPassword As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.EftPassword

instance.EftPassword = value
```

``` csharp
[ColumnAttribute("EFTPASSWORD")]
[DataMemberAttribute]
public string EftPassword { get; set; }
```

``` c++
[ColumnAttribute(L"EFTPASSWORD")]
[DataMemberAttribute]
public:
property String^ EftPassword {
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

