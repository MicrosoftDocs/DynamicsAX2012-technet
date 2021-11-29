---
title: HardwareProfilePrinter.CharacterSet Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CharacterSet Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.CharacterSet
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.characterset(v=AX.60)
ms:contentKeyID: 62204724
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.CharacterSet
dev_langs:
- CSharp
- C++
- VB
---

# CharacterSet Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the printer character set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTERCHARACTERSETVALUE")> _
<DataMemberAttribute> _
Public Property CharacterSet As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As Integer

value = instance.CharacterSet

instance.CharacterSet = value
```

``` csharp
[ColumnAttribute("PRINTERCHARACTERSETVALUE")]
[DataMemberAttribute]
public int CharacterSet { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTERCHARACTERSETVALUE")]
[DataMemberAttribute]
public:
property int CharacterSet {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The character set value.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

