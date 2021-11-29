---
title: HardwareProfile.PinPadModel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PinPadModel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadModel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.pinpadmodel(v=AX.60)
ms:contentKeyID: 62211949
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadModel
dev_langs:
- CSharp
- C++
- VB
---

# PinPadModel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the pinpad device model.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PINPADMODEL")> _
<DataMemberAttribute> _
Public Property PinPadModel As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.PinPadModel

instance.PinPadModel = value
```

``` csharp
[ColumnAttribute("PINPADMODEL")]
[DataMemberAttribute]
public string PinPadModel { get; set; }
```

``` c++
[ColumnAttribute(L"PINPADMODEL")]
[DataMemberAttribute]
public:
property String^ PinPadModel {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The model string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

