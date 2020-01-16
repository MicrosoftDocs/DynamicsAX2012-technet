---
title: HardwareProfilePrinter.Logo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Logo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.Logo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.logo(v=AX.60)
ms:contentKeyID: 62205859
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.Logo
dev_langs:
- CSharp
- C++
- VB
---

# Logo Property

Gets or sets the printer logo type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTERLOGOVALUE")> _
<DataMemberAttribute> _
Public Property Logo As PrinterLogotype
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As PrinterLogotype

value = instance.Logo

instance.Logo = value
```

``` csharp
[ColumnAttribute("PRINTERLOGOVALUE")]
[DataMemberAttribute]
public PrinterLogotype Logo { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTERLOGOVALUE")]
[DataMemberAttribute]
public:
property PrinterLogotype Logo {
    PrinterLogotype get ();
    void set (PrinterLogotype value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PrinterLogotype](printerlogotype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The PrinterLogoType value.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

