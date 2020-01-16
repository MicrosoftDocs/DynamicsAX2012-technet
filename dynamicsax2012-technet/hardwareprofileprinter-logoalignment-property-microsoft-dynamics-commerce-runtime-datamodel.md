---
title: HardwareProfilePrinter.LogoAlignment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogoAlignment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.LogoAlignment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.logoalignment(v=AX.60)
ms:contentKeyID: 62214943
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.LogoAlignment
dev_langs:
- CSharp
- C++
- VB
---

# LogoAlignment Property

Gets or sets the printer logo alignment type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTERLOGOALIGNMENTVALUE")> _
Public Property LogoAlignment As PrinterLogoAlignmentType
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As PrinterLogoAlignmentType

value = instance.LogoAlignment

instance.LogoAlignment = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTERLOGOALIGNMENTVALUE")]
public PrinterLogoAlignmentType LogoAlignment { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTERLOGOALIGNMENTVALUE")]
public:
property PrinterLogoAlignmentType LogoAlignment {
    PrinterLogoAlignmentType get ();
    void set (PrinterLogoAlignmentType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PrinterLogoAlignmentType](printerlogoalignmenttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The PrinterLogoAlignmentType value.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

