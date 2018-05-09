---
title: HardwareProfilePrinter.DeviceMake Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceMake Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceMake
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.devicemake(v=AX.60)
ms:contentKeyID: 62208888
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceMake
dev_langs:
- CSharp
- C++
- VB
---

# DeviceMake Property

Gets or sets the printer device make.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTERMAKEVALUE")> _
<DataMemberAttribute> _
Public Property DeviceMake As String
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As String

value = instance.DeviceMake

instance.DeviceMake = value
```

``` csharp
[ColumnAttribute("PRINTERMAKEVALUE")]
[DataMemberAttribute]
public string DeviceMake { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTERMAKEVALUE")]
[DataMemberAttribute]
public:
property String^ DeviceMake {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The make string.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

