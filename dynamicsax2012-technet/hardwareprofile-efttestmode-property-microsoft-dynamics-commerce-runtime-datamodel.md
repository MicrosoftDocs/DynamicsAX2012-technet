---
title: HardwareProfile.EftTestMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftTestMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftTestMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.efttestmode(v=AX.60)
ms:contentKeyID: 65318469
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftTestMode
dev_langs:
- CSharp
- C++
- VB
---

# EftTestMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EFTTESTMODE")> _
<DataMemberAttribute> _
Public Property EftTestMode As Boolean
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Boolean

value = instance.EftTestMode

instance.EftTestMode = value
```

``` csharp
[ColumnAttribute("EFTTESTMODE")]
[DataMemberAttribute]
public bool EftTestMode { get; set; }
```

``` c++
[ColumnAttribute(L"EFTTESTMODE")]
[DataMemberAttribute]
public:
property bool EftTestMode {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

