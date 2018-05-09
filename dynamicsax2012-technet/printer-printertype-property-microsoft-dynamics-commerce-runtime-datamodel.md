---
title: Printer.PrinterType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrinterType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.PrinterType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.printer.printertype(v=AX.60)
ms:contentKeyID: 62202102
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.PrinterType
dev_langs:
- CSharp
- C++
- VB
---

# PrinterType Property

Gets or sets the the type of the printer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTER")> _
Public Property PrinterType As Integer
    Get
    Set
'Usage
Dim instance As Printer
Dim value As Integer

value = instance.PrinterType

instance.PrinterType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTER")]
public int PrinterType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTER")]
public:
property int PrinterType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Printer Class](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

