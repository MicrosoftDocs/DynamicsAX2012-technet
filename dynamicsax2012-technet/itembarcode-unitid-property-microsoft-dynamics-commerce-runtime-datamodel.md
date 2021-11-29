---
title: ItemBarcode.UnitId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.UnitId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.unitid(v=AX.60)
ms:contentKeyID: 62208423
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.UnitId
dev_langs:
- CSharp
- C++
- VB
---

# UnitId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Unit Identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("UNITID")> _
Public Property UnitId As String
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As String

value = instance.UnitId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("UNITID")]
public string UnitId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"UNITID")]
public:
property String^ UnitId {
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

