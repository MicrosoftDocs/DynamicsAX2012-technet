---
title: HardwareProfile.EftUserId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftUserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTUserId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.eftuserid(v=AX.60)
ms:contentKeyID: 62205365
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftUserId
dev_langs:
- CSharp
- C++
- VB
---

# EftUserId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EFTUSERID")> _
<DataMemberAttribute> _
Public Property EftUserId As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.EftUserId

instance.EftUserId = value
```

``` csharp
[ColumnAttribute("EFTUSERID")]
[DataMemberAttribute]
public string EftUserId { get; set; }
```

``` c++
[ColumnAttribute(L"EFTUSERID")]
[DataMemberAttribute]
public:
property String^ EftUserId {
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

