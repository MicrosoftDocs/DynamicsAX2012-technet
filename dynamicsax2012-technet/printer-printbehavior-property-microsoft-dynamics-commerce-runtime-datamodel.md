---
title: Printer.PrintBehavior Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintBehavior Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.PrintBehavior
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.printer.printbehavior(v=AX.60)
ms:contentKeyID: 62208289
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.PrintBehavior
dev_langs:
- CSharp
- C++
- VB
---

# PrintBehavior Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the print behavior of the receipt format.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTBEHAVIOUR")> _
<IgnoreDataMemberAttribute> _
Public Property PrintBehavior As PrintBehavior
    Get
    Set
'Usage
Dim instance As Printer
Dim value As PrintBehavior

value = instance.PrintBehavior

instance.PrintBehavior = value
```

``` csharp
[ColumnAttribute("PRINTBEHAVIOUR")]
[IgnoreDataMemberAttribute]
public PrintBehavior PrintBehavior { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTBEHAVIOUR")]
[IgnoreDataMemberAttribute]
public:
property PrintBehavior PrintBehavior {
    PrintBehavior get ();
    void set (PrintBehavior value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PrintBehavior](printbehavior-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PrintBehavior](printbehavior-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Printer Class](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

