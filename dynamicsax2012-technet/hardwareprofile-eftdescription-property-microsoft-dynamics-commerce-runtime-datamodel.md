---
title: HardwareProfile.EftDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftdescription(v=AX.60)
ms:contentKeyID: 62206919
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftDescription
dev_langs:
- CSharp
- C++
- VB
---

# EftDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EFTDESCRIPTION")> _
Public Property EftDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.EftDescription

instance.EftDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EFTDESCRIPTION")]
public string EftDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EFTDESCRIPTION")]
public:
property String^ EftDescription {
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

