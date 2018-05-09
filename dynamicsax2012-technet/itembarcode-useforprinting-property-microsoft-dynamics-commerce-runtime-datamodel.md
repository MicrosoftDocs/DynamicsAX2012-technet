---
title: ItemBarcode.UseForPrinting Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseForPrinting Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.UseForPrinting
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.useforprinting(v=AX.60)
ms:contentKeyID: 62211901
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.UseForPrinting
dev_langs:
- CSharp
- C++
- VB
---

# UseForPrinting Property

Gets the flag whether the Barcode is used for Printing.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("USEFORPRINTING")> _
<DataMemberAttribute> _
Public Property UseForPrinting As String
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As String

value = instance.UseForPrinting
```

``` csharp
[ColumnAttribute("USEFORPRINTING")]
[DataMemberAttribute]
public string UseForPrinting { get; internal set; }
```

``` c++
[ColumnAttribute(L"USEFORPRINTING")]
[DataMemberAttribute]
public:
property String^ UseForPrinting {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemBarcode Class](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

