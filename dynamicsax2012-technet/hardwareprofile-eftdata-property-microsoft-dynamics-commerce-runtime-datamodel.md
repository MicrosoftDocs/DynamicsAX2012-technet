---
title: HardwareProfile.EftData Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftdata(v=AX.60)
ms:contentKeyID: 62211509
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftData
dev_langs:
- CSharp
- C++
- VB
---

# EftData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EFTDATA")> _
<DataMemberAttribute> _
Public Property EftData As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.EftData

instance.EftData = value
```

``` csharp
[ColumnAttribute("EFTDATA")]
[DataMemberAttribute]
public string EftData { get; set; }
```

``` c++
[ColumnAttribute(L"EFTDATA")]
[DataMemberAttribute]
public:
property String^ EftData {
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

