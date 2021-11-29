---
title: HardwareProfilePrinter.BinaryConversion Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BinaryConversion Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.BinaryConversion
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.binaryconversion(v=AX.60)
ms:contentKeyID: 62215208
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.BinaryConversion
dev_langs:
- CSharp
- C++
- VB
---

# BinaryConversion Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether binary conversion is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTERBINARYCONVERSIONVALUE")> _
Public Property BinaryConversion As Boolean
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As Boolean

value = instance.BinaryConversion

instance.BinaryConversion = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTERBINARYCONVERSIONVALUE")]
public bool BinaryConversion { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTERBINARYCONVERSIONVALUE")]
public:
property bool BinaryConversion {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if binary conversion is set; otherwise, false.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

