---
title: ItemBarcode.RetailShowForItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailShowForItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.RetailShowForItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.retailshowforitem(v=AX.60)
ms:contentKeyID: 62209637
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.RetailShowForItem
dev_langs:
- CSharp
- C++
- VB
---

# RetailShowForItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether Item shown for Retail.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETAILSHOWFORITEM")> _
Public Property RetailShowForItem As Boolean
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As Boolean

value = instance.RetailShowForItem
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETAILSHOWFORITEM")]
public bool RetailShowForItem { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETAILSHOWFORITEM")]
public:
property bool RetailShowForItem {
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

