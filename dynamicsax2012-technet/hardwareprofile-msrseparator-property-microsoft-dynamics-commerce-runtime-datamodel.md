---
title: HardwareProfile.MsrSeparator Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MsrSeparator Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MSRSeparator
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.msrseparator(v=AX.60)
ms:contentKeyID: 62211858
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MsrSeparator
dev_langs:
- CSharp
- C++
- VB
---

# MsrSeparator Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SEPARATOR1")> _
Public Property MsrSeparator As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.MsrSeparator

instance.MsrSeparator = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SEPARATOR1")]
public string MsrSeparator { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SEPARATOR1")]
public:
property String^ MsrSeparator {
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

