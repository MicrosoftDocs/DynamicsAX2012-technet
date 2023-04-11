---
title: Printer.Name Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Name Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.Name
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.printer.name(v=AX.60)
ms:contentKeyID: 62212361
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.Name
dev_langs:
- CSharp
- C++
- VB
---

# Name Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the name of the printer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTERDEVICENAME")> _
<DataMemberAttribute> _
Public Property Name As String
    Get
    Set
'Usage
Dim instance As Printer
Dim value As String

value = instance.Name

instance.Name = value
```

``` csharp
[ColumnAttribute("PRINTERDEVICENAME")]
[DataMemberAttribute]
public string Name { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTERDEVICENAME")]
[DataMemberAttribute]
public:
property String^ Name {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Printer Class](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

