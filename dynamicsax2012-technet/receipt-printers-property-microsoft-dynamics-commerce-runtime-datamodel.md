---
title: Receipt.Printers Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Printers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt.Printers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receipt.printers(v=AX.60)
ms:contentKeyID: 62214388
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt.Printers
dev_langs:
- CSharp
- C++
- VB
---

# Printers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the printers that can print the receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Printers As ICollection(Of Printer)
    Get
    Set
'Usage
Dim instance As Receipt
Dim value As ICollection(Of Printer)

value = instance.Printers

instance.Printers = value
```

``` csharp
[DataMemberAttribute]
public ICollection<Printer> Printers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<Printer^>^ Printers {
    ICollection<Printer^>^ get ();
    void set (ICollection<Printer^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Printer](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[Receipt Class](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

