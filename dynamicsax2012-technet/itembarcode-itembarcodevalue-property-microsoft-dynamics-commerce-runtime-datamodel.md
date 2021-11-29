---
title: ItemBarcode.ItemBarcodeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemBarcodeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.ItemBarcodeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.itembarcodevalue(v=AX.60)
ms:contentKeyID: 62209024
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.ItemBarcodeValue
dev_langs:
- CSharp
- C++
- VB
---

# ItemBarcodeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item's barcode idenfitier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ITEMBARCODE")> _
Public Property ItemBarcodeValue As String
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As String

value = instance.ItemBarcodeValue
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ITEMBARCODE")]
public string ItemBarcodeValue { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ITEMBARCODE")]
public:
property String^ ItemBarcodeValue {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemBarcode Class](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

