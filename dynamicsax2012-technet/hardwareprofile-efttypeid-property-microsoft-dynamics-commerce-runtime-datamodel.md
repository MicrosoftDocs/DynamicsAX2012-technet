---
title: HardwareProfile.EftTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EftTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EFTTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.efttypeid(v=AX.60)
ms:contentKeyID: 62210531
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.EftTypeId
dev_langs:
- CSharp
- C++
- VB
---

# EftTypeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EFT")> _
Public Property EftTypeId As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Integer

value = instance.EftTypeId

instance.EftTypeId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EFT")]
public int EftTypeId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EFT")]
public:
property int EftTypeId {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

