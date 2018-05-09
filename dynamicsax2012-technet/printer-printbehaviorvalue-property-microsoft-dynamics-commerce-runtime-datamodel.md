---
title: Printer.PrintBehaviorValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintBehaviorValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.PrintBehaviorValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.printer.printbehaviorvalue(v=AX.60)
ms:contentKeyID: 62209539
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.PrintBehaviorValue
dev_langs:
- CSharp
- C++
- VB
---

# PrintBehaviorValue Property

Gets or sets the value of the PrintBehavior enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PrintBehaviorValue As Integer
    Get
    Set
'Usage
Dim instance As Printer
Dim value As Integer

value = instance.PrintBehaviorValue

instance.PrintBehaviorValue = value
```

``` csharp
[DataMemberAttribute]
public int PrintBehaviorValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int PrintBehaviorValue {
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

