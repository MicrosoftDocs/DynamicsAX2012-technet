---
title: HardwareProfilePrinter.DeviceDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.devicedescription(v=AX.60)
ms:contentKeyID: 62212872
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# DeviceDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the printer device description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTERDESCRIPTIONVALUE")> _
Public Property DeviceDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As String

value = instance.DeviceDescription

instance.DeviceDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTERDESCRIPTIONVALUE")]
public string DeviceDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTERDESCRIPTIONVALUE")]
public:
property String^ DeviceDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The description string.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

