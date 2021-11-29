---
title: ItemBarcode.UseForInput Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseForInput Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.UseForInput
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.useforinput(v=AX.60)
ms:contentKeyID: 62205105
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.UseForInput
dev_langs:
- CSharp
- C++
- VB
---

# UseForInput Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the Barcode is used for Input.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("USEFORINPUT")> _
Public Property UseForInput As Boolean
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As Boolean

value = instance.UseForInput
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("USEFORINPUT")]
public bool UseForInput { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"USEFORINPUT")]
public:
property bool UseForInput {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ItemBarcode Class](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

