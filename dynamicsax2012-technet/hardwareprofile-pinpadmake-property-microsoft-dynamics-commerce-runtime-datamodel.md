---
title: HardwareProfile.PinPadMake Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PinPadMake Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadMake
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.pinpadmake(v=AX.60)
ms:contentKeyID: 62210843
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadMake
dev_langs:
- CSharp
- C++
- VB
---

# PinPadMake Property

Gets or sets the pinpad device make.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PINPADMAKE")> _
Public Property PinPadMake As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.PinPadMake

instance.PinPadMake = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PINPADMAKE")]
public string PinPadMake { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PINPADMAKE")]
public:
property String^ PinPadMake {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The make string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

